# latihan
06- Casting Tipe Data
# Kita belajar Casting
# merubah dari satu tipe ke tipe lain
# tipe data = int, float, str, bool

## INTEGER
print("====INTEGER====")
data_int = 9  # jika data int = 0 maka nilai boolean menjadi false dan diluar 0 akan true
print("data = ", data_int, ",type =", type(data_int))

data_float  = float(data_int)
data_str    = str(data_int)
data_bool   = bool(data_int) # akan false nilai int = 0
print("data = ", data_float, ",type =", type(data_float))
print("data = ", data_str, ",type =", type(data_str))
print("data = ", data_bool, ",type =", type(data_bool))

## FLOAT
print("====FLOAT====")
data_float = 9.9
print("data = ", data_float, ",type =", type(data_float))

data_int  = int(data_float) # akan dibulatkan ke bawah
data_str    = str(data_float)
data_bool   = bool(data_float) # akan false nilai int = 0
print("data = ", data_int, ",type =",type(data_int))
print("data = ", data_str, ",type =",type(data_str))
print("data = ", data_bool, ",type =",type(data_bool))

## BOOLEAN
print("====BOOLEAN====")
data_bool = True
print("data = ", data_bool, ",type =", type(data_bool))

data_int  = int(data_bool) # akan dibulatkan ke bawah
data_str    = str(data_bool)
data_float   = float(data_bool) # akan false nilai int = 0
print("data = ", data_int, ",type =",type(data_int))
print("data = ", data_str, ",type =",type(data_str))
print("data = ", data_float, ",type =",type(data_float))
