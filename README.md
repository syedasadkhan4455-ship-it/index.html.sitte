import { auth } from "./firebase";
import { signInWithEmailAndPassword } from "firebase/auth";

export function login() {
  let email = document.getElementById("email").value;
  let password = document.getElementById("password").value;

  signInWithEmailAndPassword(auth, email, password)
    .then(() => {
      alert("Login successful");
      window.location.href = "/dashboard";
    })
    .catch((err) => {
      alert(err.message);
    });
}
