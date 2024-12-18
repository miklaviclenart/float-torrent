# float-torrent

Projekt pri predmetu programiranje 2.

Cilj projekta je generator različnih zaporedij števil s plavajočo vejico `f64`, indeksiranih z naravnimi števili `u64`. Pri delovanju si generator zaporedja izmenjuje tudi z drugimi generatorji, ki so vsi prijavljeni v isti osrednji register. Tako register kot vsi generatorji so napisani kot spletni strežniki in eden z drugim kounicirajo prek HTTP-ja.
