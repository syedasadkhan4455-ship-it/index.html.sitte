import { db } from "./firebase";
import { collection, addDoc } from "firebase/firestore";

export async function addUser() {
  await addDoc(collection(db, "users"), {
    name: "User",
    time: new Date()
  });
}
