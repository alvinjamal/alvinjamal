// Soal 1

var nama = "Alvin Jamal Azkya";
var email = "alvinjamalazkya@gmail.com";
let alamat =
  "Kp. Godebag Rt.04 Rw.02 Ds. Tanjungkerta Kec. Pagerageung Kab. Tasikmalaya";
var isMerried = false;
var hoby = "SepakBola, Gaming";

console.log("Nama saya adalah " + nama);
console.log("Email saya adalah " + email);
console.log("Alamat saya adalah " + alamat);
console.log(isMerried);
console.log("Nama  saya adalah " + hoby);

const student = {
  firstName: "Alvin",
  lastname: "Jamal Azkya",
  country: "Indonesia",
};
const { firstName, lastname, country } =
  // Soal 2

  (angka = "");
printNumber = (num) => {
  for (let i = 1; (i = num); i++) {
    console.log(i);
  }
};
printNumber();

cekGanjil = (angka) => {
  var cekAngkaGanjil = angka % 2;
  if (cekAngkaGanjil === 1) {
    console.log(angka + "");
  } else {
    console.log(angka);
  }
};
cekGanjil(1);
cekGanjil(3);
cekGanjil(5);

// Soal 3

let n = 5; // height of pattern
let segitiga = "";
// External loop
for (let i = 0; i < 6; i++) {
  for (let j = 1; j < 5 + i - 4; j++) {
    segitiga += j;
  }
  segitiga += "\n";
}
console.log(segitiga);
