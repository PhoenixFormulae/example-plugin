<!-- LINKS -->
[phoenix-formulae]: https://phoenixformulae.com/
[phoenix-formulae-store]: https://store.phoenixformulae.com/
<!-- LINKS -->

<!-- PROJECTS -->
[projects:pxf-builder]: https://github.com/PhoenixFormulae/PxF-Builder
<!-- PROJECTS -->

<!-- OTHERS -->
[tools:github]: http://www.gihub.com/
[tools:git]: https://git-scm.com/
<!-- OTHERS -->


# Example Plugin Repository
[![PhoenixFormulae-Store](https://img.shields.io/badge/PhoenixFormulae-Store-orange.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAFfKj%2FFAAAACXBIWXMAAA7EAAAOxAGVKw4bAAACIlBMVEWAgICecWhsbG3Xjitra2pQUFBvcnSJhoGNiIGPioNMSkh5gYuKenZ5ho1VX2duZ1eYin1YZGx0bFmaj4KdkoSgjHpuh5ummHFti6O1imVtiZ9sjKOsl4C2iWiyk3iUXlGNeUp7ZjpTdY5sjKVsjKWXf0jCpYSeUj%2BaRjPakjvLo306a5GmdFlRiLJvh5u5kj68cz1SksTAljzZm2bktVNRksVOksbnuFPbq0XkoUjSj2JNkshdnc9SlcnajUfwwVvrsEnVgTxOls%2FHeVC6tF7zx02%2BZ0D1wE1Ilc%2Fxx2tem7%2BAlKb6v1KHjoqjmGl5obuGqY2HoJiPoYfipSbmYSgAAABFkcxFks5HldFIldFboNZdmrhqlKVrka9xla19oJKMut2OfXOQk3yTgYOcmXeliGSnyeO1dS24n165XC66nmS6n4q%2Bc1u%2Bwo%2FLczXWsYXZxHzfwyDgkDfhkRTjlxrnKBHoOhnomBHouRPo0x3qKR7qUiDqf0XqhzXrYyXsNyPsZSbsaQrsbA7sbivtWiLtcAztdi7ucSbufzDuqRLuzxDvcBjvkiXwgC3xjSbyhx70ijv0lkX00Bv1gTz1lyL1l0T1ny71p131y3D2lUP2mzf2pTn2pkj2sW72zof3lj%2F3p1H3sg%2F3s2P3tGr5sCr6tkn6xFr6yQz6yj%2F71YX82AP824f9yFr90zf92hr94wX%2Bw1D%2BxFD%2BxVD%2BxlD%2B3Zf%2FyFHSXopCAAAAVXRSTlMAAQUFBgkJCgsMDxAQEiUmJisrKzAwOT5ITU5SU1RZWmBiZ2pscHaMl5ekp6eptba3wMLHyMnR0tfY2dra3d3d4OLk6ert7%2FT5%2Bfr7%2B%2F39%2Fv7%2B%2Fv7%2BeqFSlgAAAAFiS0dEVZMEuDMAAAEASURBVBgZNcEDV55hAIDhO9vGsrGs5bZsnHrism3btu1aXt%2F%2F661zui4kP2eRdDzhEiiAkE19zEAFk1wRTWVm2jjap%2FuKaKoaF4gY%2FPBYF6K4%2FHEOu4bjronDnQfARvaWCOjy6Qf8IkzkmxrKEUeeEKGWrtT8FaIi676d5rbU%2Bpz57RXSW5ZXB47OZcjr7fUvROkgiX%2FddUTiZgQa5vYOFlpg5QTWv9XwKa0WkgAMIhRwrvsTniC%2BJEXGdvbgXdbXWyQKa4eGqzKebxan8CxpbcoeOzmYHj27vbu%2BkqHsntw4eDE5stS9NbOW4mXLJ%2F%2F%2FLxuX%2F96D%2BKbkK5MEqyP5AA1%2FSyF%2FKQx0AAAAAElFTkSuQmCC
)][phoenix-formulae-store]
![PhoenixFormulae-Plugin](https://img.shields.io/badge/PhoenixFormulae-Plugin-orange.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAFfKj%2FFAAAACXBIWXMAAA7EAAAOxAGVKw4bAAACIlBMVEWAgICecWhsbG3Xjitra2pQUFBvcnSJhoGNiIGPioNMSkh5gYuKenZ5ho1VX2duZ1eYin1YZGx0bFmaj4KdkoSgjHpuh5ummHFti6O1imVtiZ9sjKOsl4C2iWiyk3iUXlGNeUp7ZjpTdY5sjKVsjKWXf0jCpYSeUj%2BaRjPakjvLo306a5GmdFlRiLJvh5u5kj68cz1SksTAljzZm2bktVNRksVOksbnuFPbq0XkoUjSj2JNkshdnc9SlcnajUfwwVvrsEnVgTxOls%2FHeVC6tF7zx02%2BZ0D1wE1Ilc%2Fxx2tem7%2BAlKb6v1KHjoqjmGl5obuGqY2HoJiPoYfipSbmYSgAAABFkcxFks5HldFIldFboNZdmrhqlKVrka9xla19oJKMut2OfXOQk3yTgYOcmXeliGSnyeO1dS24n165XC66nmS6n4q%2Bc1u%2Bwo%2FLczXWsYXZxHzfwyDgkDfhkRTjlxrnKBHoOhnomBHouRPo0x3qKR7qUiDqf0XqhzXrYyXsNyPsZSbsaQrsbA7sbivtWiLtcAztdi7ucSbufzDuqRLuzxDvcBjvkiXwgC3xjSbyhx70ijv0lkX00Bv1gTz1lyL1l0T1ny71p131y3D2lUP2mzf2pTn2pkj2sW72zof3lj%2F3p1H3sg%2F3s2P3tGr5sCr6tkn6xFr6yQz6yj%2F71YX82AP824f9yFr90zf92hr94wX%2Bw1D%2BxFD%2BxVD%2BxlD%2B3Zf%2FyFHSXopCAAAAVXRSTlMAAQUFBgkJCgsMDxAQEiUmJisrKzAwOT5ITU5SU1RZWmBiZ2pscHaMl5ekp6eptba3wMLHyMnR0tfY2dra3d3d4OLk6ert7%2FT5%2Bfr7%2B%2F39%2Fv7%2B%2Fv7%2BeqFSlgAAAAFiS0dEVZMEuDMAAAEASURBVBgZNcEDV55hAIDhO9vGsrGs5bZsnHrism3btu1aXt%2F%2F661zui4kP2eRdDzhEiiAkE19zEAFk1wRTWVm2jjap%2FuKaKoaF4gY%2FPBYF6K4%2FHEOu4bjronDnQfARvaWCOjy6Qf8IkzkmxrKEUeeEKGWrtT8FaIi676d5rbU%2Bpz57RXSW5ZXB47OZcjr7fUvROkgiX%2FddUTiZgQa5vYOFlpg5QTWv9XwKa0WkgAMIhRwrvsTniC%2BJEXGdvbgXdbXWyQKa4eGqzKebxan8CxpbcoeOzmYHj27vbu%2BkqHsntw4eDE5stS9NbOW4mXLJ%2F%2F%2FLxuX%2F96D%2BKbkK5MEqyP5AA1%2FSyF%2FKQx0AAAAAElFTkSuQmCC
)

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)][tools:github]
[![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)][tools:git]

This repository is an example of how to set up a PxF Plugin
for PxF Store and PxF Integrator, the repository has to follow all the conditions to be eligible:
 - Plugin Content (Cythonized)
 - GitHub Actions CI / CD building packed plugin on demand
 - Store Product content
 
<br />


### Setting up Plugin content
[![PhoenixFormulae-Builder](https://img.shields.io/badge/PhoenixFormulae-Builder-orange.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAFfKj%2FFAAAACXBIWXMAAA7EAAAOxAGVKw4bAAACIlBMVEWAgICecWhsbG3Xjitra2pQUFBvcnSJhoGNiIGPioNMSkh5gYuKenZ5ho1VX2duZ1eYin1YZGx0bFmaj4KdkoSgjHpuh5ummHFti6O1imVtiZ9sjKOsl4C2iWiyk3iUXlGNeUp7ZjpTdY5sjKVsjKWXf0jCpYSeUj%2BaRjPakjvLo306a5GmdFlRiLJvh5u5kj68cz1SksTAljzZm2bktVNRksVOksbnuFPbq0XkoUjSj2JNkshdnc9SlcnajUfwwVvrsEnVgTxOls%2FHeVC6tF7zx02%2BZ0D1wE1Ilc%2Fxx2tem7%2BAlKb6v1KHjoqjmGl5obuGqY2HoJiPoYfipSbmYSgAAABFkcxFks5HldFIldFboNZdmrhqlKVrka9xla19oJKMut2OfXOQk3yTgYOcmXeliGSnyeO1dS24n165XC66nmS6n4q%2Bc1u%2Bwo%2FLczXWsYXZxHzfwyDgkDfhkRTjlxrnKBHoOhnomBHouRPo0x3qKR7qUiDqf0XqhzXrYyXsNyPsZSbsaQrsbA7sbivtWiLtcAztdi7ucSbufzDuqRLuzxDvcBjvkiXwgC3xjSbyhx70ijv0lkX00Bv1gTz1lyL1l0T1ny71p131y3D2lUP2mzf2pTn2pkj2sW72zof3lj%2F3p1H3sg%2F3s2P3tGr5sCr6tkn6xFr6yQz6yj%2F71YX82AP824f9yFr90zf92hr94wX%2Bw1D%2BxFD%2BxVD%2BxlD%2B3Zf%2FyFHSXopCAAAAVXRSTlMAAQUFBgkJCgsMDxAQEiUmJisrKzAwOT5ITU5SU1RZWmBiZ2pscHaMl5ekp6eptba3wMLHyMnR0tfY2dra3d3d4OLk6ert7%2FT5%2Bfr7%2B%2F39%2Fv7%2B%2Fv7%2BeqFSlgAAAAFiS0dEVZMEuDMAAAEASURBVBgZNcEDV55hAIDhO9vGsrGs5bZsnHrism3btu1aXt%2F%2F661zui4kP2eRdDzhEiiAkE19zEAFk1wRTWVm2jjap%2FuKaKoaF4gY%2FPBYF6K4%2FHEOu4bjronDnQfARvaWCOjy6Qf8IkzkmxrKEUeeEKGWrtT8FaIi676d5rbU%2Bpz57RXSW5ZXB47OZcjr7fUvROkgiX%2FddUTiZgQa5vYOFlpg5QTWv9XwKa0WkgAMIhRwrvsTniC%2BJEXGdvbgXdbXWyQKa4eGqzKebxan8CxpbcoeOzmYHj27vbu%2BkqHsntw4eDE5stS9NbOW4mXLJ%2F%2F%2FLxuX%2F96D%2BKbkK5MEqyP5AA1%2FSyF%2FKQx0AAAAAElFTkSuQmCC
)][projects:pxf-builder]

Plugin source content should be placed under `/plugin`  directory, the content
should be the plugin source cythonized using [PxF Builder][projects:pxf-builder]


### Setting up GitHub Actions
![GitHub Actions](https://img.shields.io/badge/githubactions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)

In development



### Setting up PxF Store Product Page content
[![PhoenixFormulae-Store](https://img.shields.io/badge/PhoenixFormulae-Store-orange.svg?style=for-the-badge&logo=data%3Aimage%2Fpng%3Bbase64%2CiVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAFfKj%2FFAAAACXBIWXMAAA7EAAAOxAGVKw4bAAACIlBMVEWAgICecWhsbG3Xjitra2pQUFBvcnSJhoGNiIGPioNMSkh5gYuKenZ5ho1VX2duZ1eYin1YZGx0bFmaj4KdkoSgjHpuh5ummHFti6O1imVtiZ9sjKOsl4C2iWiyk3iUXlGNeUp7ZjpTdY5sjKVsjKWXf0jCpYSeUj%2BaRjPakjvLo306a5GmdFlRiLJvh5u5kj68cz1SksTAljzZm2bktVNRksVOksbnuFPbq0XkoUjSj2JNkshdnc9SlcnajUfwwVvrsEnVgTxOls%2FHeVC6tF7zx02%2BZ0D1wE1Ilc%2Fxx2tem7%2BAlKb6v1KHjoqjmGl5obuGqY2HoJiPoYfipSbmYSgAAABFkcxFks5HldFIldFboNZdmrhqlKVrka9xla19oJKMut2OfXOQk3yTgYOcmXeliGSnyeO1dS24n165XC66nmS6n4q%2Bc1u%2Bwo%2FLczXWsYXZxHzfwyDgkDfhkRTjlxrnKBHoOhnomBHouRPo0x3qKR7qUiDqf0XqhzXrYyXsNyPsZSbsaQrsbA7sbivtWiLtcAztdi7ucSbufzDuqRLuzxDvcBjvkiXwgC3xjSbyhx70ijv0lkX00Bv1gTz1lyL1l0T1ny71p131y3D2lUP2mzf2pTn2pkj2sW72zof3lj%2F3p1H3sg%2F3s2P3tGr5sCr6tkn6xFr6yQz6yj%2F71YX82AP824f9yFr90zf92hr94wX%2Bw1D%2BxFD%2BxVD%2BxlD%2B3Zf%2FyFHSXopCAAAAVXRSTlMAAQUFBgkJCgsMDxAQEiUmJisrKzAwOT5ITU5SU1RZWmBiZ2pscHaMl5ekp6eptba3wMLHyMnR0tfY2dra3d3d4OLk6ert7%2FT5%2Bfr7%2B%2F39%2Fv7%2B%2Fv7%2BeqFSlgAAAAFiS0dEVZMEuDMAAAEASURBVBgZNcEDV55hAIDhO9vGsrGs5bZsnHrism3btu1aXt%2F%2F661zui4kP2eRdDzhEiiAkE19zEAFk1wRTWVm2jjap%2FuKaKoaF4gY%2FPBYF6K4%2FHEOu4bjronDnQfARvaWCOjy6Qf8IkzkmxrKEUeeEKGWrtT8FaIi676d5rbU%2Bpz57RXSW5ZXB47OZcjr7fUvROkgiX%2FddUTiZgQa5vYOFlpg5QTWv9XwKa0WkgAMIhRwrvsTniC%2BJEXGdvbgXdbXWyQKa4eGqzKebxan8CxpbcoeOzmYHj27vbu%2BkqHsntw4eDE5stS9NbOW4mXLJ%2F%2F%2FLxuX%2F96D%2BKbkK5MEqyP5AA1%2FSyF%2FKQx0AAAAAElFTkSuQmCC
)][phoenix-formulae-store]

Content that shows up at the product page on the store should be
placed under a directory called `/store`

The product page construction uses [reST](https://docutils.sourceforge.io/rst.html) to display the page information

To construct the product page information, you can make a file called `index.rst`, 
other information to be displayed in product page should be placed in `/store/about`

Images to be shown in the product page should be placed in `/store/showcase` directory

