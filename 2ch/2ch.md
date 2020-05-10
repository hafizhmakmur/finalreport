## Bab 2
 
### Metode Formal [^Hinchey1995]
* Apa itu metode formal (Definisi, Penemu, Filosofi) [^Monin2003]   
  Menurut Monin, sebenarnya istilah Teknik Formal lebih pantas untuk 
  digunakan dibandingkan Metode Formal karena teknik ini belum memiliki
  metodologi yang baku. Namun karena istilah Metode Formal lebih 
  populer maka untuk selanjutnya dalam tulisan ini istilah Metode
  Formal lah yang akn digunakan.
* Kenapa metode formal [^Holloway1997]
* Software Engineering jauh lebih tidak reliable dari other eng
* Kenapa metode formal jarang dipake
* Contoh metode formal yang sudah dipake
* Kelemahan Metode Formal

#### Justifikasi Logis [^Huth2004]
* Aturan Logis
* Logika Propositional
* Logika Predikat
* SAT and SMT Solver

#### Spesifikasi Program
* Desain sebelum kode
* Test Driven Development

#### Verifikasi Program
* Verifikasi dengan Model Checking (Model Based)
* Verifikasi dengan Semantic Entailment (Proof Based)

### Pemrograman Fungsional
* Paradigma Pemrograman [^Harper2017]
* Paradigma Pemrograman Fungsional [^Sabry1998]
* Paradigram Pemrograman Fungsional Murni
* Kenapa Fungsional Murni itu excellent buat Metode Formal
[^Turner1985] [^Hughes1989] [^Butler1995]
* Perbandingan dengan Paradigma lain

#### Haskell [^O'Sullivan2008]
* Definisi, Penemu, Filosofi [^Hudak2007]
* Fungsional Murni
* Lazy Computing
* Hard Typing
* Program yang dibuat menggunakan Haskell (Hackage)
* How to Specify and Verify (Haskell for Specification)

#### Liquid Haskell [^Pena2017]
* Definisi, Penemu, Filosofi  
  Liquid Haskell merupakan sebuah _type-checker_ untuk bahasa 
  fungsional Haskell yang bertujuan untuk membantu memudahkan 
  pemrogram untuk memverifikasi program mereka dengan usaha 
  sesedikit mungkin. Untuk itu _type-checker_ ini menggunakan sebuah
  teknologi bernama _Liquid Types_ yang merupakan singkatan dari 
  _Logically Qualified Data Types_. Pada dasarnya, teknologi ini 
  menggunakan SMT Solver untuk secara instan memverifikasi sebuah 
  program yang sudah dituliskan spesifikasinya dalam _Liquid Types_.
  Dengan itu, tidaklah lagi diperlukan waktu yang panjang untuk 
  memverifikasi program dengan menuliskan persamaan matematika dengan
  tangan karena hal itu sudah bisa ditangani oleh komputer.
* Liquid Types
* Usage of SMT Solver in Liquid Haskell
* Kelemahan Liquid Haskell
* Refinement, Inference, and Polymorphism
* Liquid haskell Case Studies

#### Concurrency in Haskell

[^Hinchey1995]: Hinchey, M.G., & Bowen J. (ed) (1995). _Applications of 
  Formal Methods._ Hertfordshire, UK: Prentice Hall.
[^Huth2004]: Huth, M., & Ryan M. (2004). _Logic in Computer Science._ 
  New York, NY: Cambridge University Press
[^O'Sullivan2008]: O'Sullivan, B., Stewart D., & Goerzen J. (2008). 
  _Real World Haskell_, Massachusets, MA: O'Reilly.
[^Hudak2007]: Hudak, P., Hughes, J., Jones S.P., & Wadler P. (2007). 
  A History of Haskell: Being Lazy With Class. Prosiding _The Third 
  ACM SIGPLAN conference on History of Programming Languages_, 
  12-1-12-55. New York, NY: ACM Press.
[^Pena2017]: Pena, R. (2017). An Introduction to Liquid Haskell. 
  _EPCTS 237_, 68-80
[^Turner1985]: Turner, D.A. (1985) Miranda - a non-strict 
  functional language with polymorphic types. In: Jouannaud, J.-P. 
  (ed.) FPCA 1985. LNCS, vol. 201, pp. 1–16. Springer, Heidelberg
[^Hughes1989]: Hughes, J. (1989). Why Functional Programming Matters. 
  _The Computer Journal_ 32(2), 98–107 
[^Butler1995]: Butler, J. (1995). Use of a functional programming 
  language for formal specification, 
  _IEE Colloquium on Practical Application of Formal 
  Methods_, London, UK, pp. 2/1-2/3.
[^Sabry1998]: Sabry, A. (1998). What is a purely functional language?. 
  _Journal of Functional Programming_, 8(1), 1-22. 
[^Harper2017]: Harper, R. (2017). _What, if anything, is a
  programming-paradigm?_. FifteenEightyFour. Cambridge University Press.
[^Holloway1997]: Holloway, C.M. (1997). Why engineers should consider formal
  methods. Prosiding _16th DASC. AIAA/IEEE Digital Avionics Systems 
  Conference. Reflections to the Future_. Irvine, CA, pp. 1.3-16
[^Monin2003]: Monin, J, & Hinchey, M. (2003). _Understanding
  Formal Methods_. London, UK: Springer-Verlag
