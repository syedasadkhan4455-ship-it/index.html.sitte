import { auth } from "./firebase";
import { signOut } from "firebase/auth";

export function logout() {
  signOut(auth).then(() => {
    alert("Logged out");
    window.location.href = "/";
  });
}
