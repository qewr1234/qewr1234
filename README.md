- š Hi, Iām @qewr1234
- š Iām interested in ...
- š± Iām currently learning ...
- šļø Iām looking to collaborate on ...
- š« How to reach me ...

<!---
qewr1234/qewr1234 is a āØ special āØ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

class cmplx:
    def __init__(self, real = 0.0, imagin = 0.0):
        self.real = real
        self.imagin = imagin

    def __add__(self, other):
        r = self.real + other.real
        i = self.imagin + other.imagin
        return cmplx(r, i)

    def __sub__ (self, other):
        r = self.real - other.real
        i = self.imagin - other.imagin
        return cmplx(r, i)

    def __mul__(self, other):
        r = self.real * other.real - self.imagin * other.imagin
        i = self.real * other.real + self.imagin * other.imagin
        return cmplx(r, i)

    def __str__(self):
        s = "cmplx({:>8.4}, {:>8.4})".format(self.real, self.imagin)
        return s

