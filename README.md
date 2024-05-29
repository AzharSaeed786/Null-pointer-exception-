# Null-pointer-exception-
Null Pointer Exception Kotlin programming language ka aik ahem concept hai. Jab aik variable ya object jo null (khali) ho, usay access ya use karna ki koshish ki jati hai, tab Null Pointer Exception hoti hai.

Kotlin ma, Null Pointer Exception ko handle karna kaafi asan hai, kyunki Kotlin aik null-safety mechanism provide karta hai. Ye kuch tareeqay hain jinse aap Null Pointer Exception se bach sakte hain
Nullable Types:
Kotlin ma aapko explicitly declare karna parta hai agar aik variable null ho sakta hai. Yeh question mark ? laga kar kiya jata hai.
Safe Call Operator ?.:
Aap safe call operator use kar sakte hain agar aik nullable variable ko access karna ho. Agar variable null ho, to expression null return karega aur koi exception nahi throw hogi.
Elvis Operator ?::
Ye operator default value provide karne ke liye use hota hai agar variable null ho.
