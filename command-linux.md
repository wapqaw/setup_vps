# Pencarian Directory yang Memiliki Ukuran Besar:
Command berikut akan melakukan pencarian 10 directory dengan penggunaan disk paling besar di server Anda<br/>
du -ahx / | sort -rh | head -10

# Pencarian File yang Memiliki Ukuran Besar:
Command dibawah berfungsi untuk mencari file terbesar pada seluruh direktori dan mengurutkannya dalam 10 terbesar.<br/>
find / -xdev -type f -size +50M -exec du -sh {} ';' | sort -rh | head -n10

# Listing Ukuran File dan Directory:
Command dibawah ini berfungsi untuk listing ukuran folder untuk mengetahui sizenya<br/>
du -hsx * | sort -rh
