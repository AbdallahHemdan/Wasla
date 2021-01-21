<div align="center">

![component 17](https://user-images.githubusercontent.com/40190772/105380975-27670c00-5c17-11eb-9158-b39d562e7b9f.png)


</div>

<div align="center">

[![GitHub contributors](https://img.shields.io/github/contributors/AbdallahHemdan/Wasla)](https://github.com/AbdallahHemdan/Wasla/contributors)
[![GitHub issues](https://img.shields.io/github/issues/AbdallahHemdan/Wasla)](https://github.com/AbdallahHemdan/Wasla/issues)
[![GitHub forks](https://img.shields.io/github/forks/AbdallahHemdan/Wasla)](https://github.com/AbdallahHemdan/Wasla/network)
[![GitHub stars](https://img.shields.io/github/stars/AbdallahHemdan/Wasla)](https://github.com/AbdallahHemdan/Wasla/stargazers)
[![GitHub license](https://img.shields.io/github/license/AbdallahHemdan/Wasla)](https://github.com/AbdallahHemdan/Wasla/blob/master/LICENSE)
<img src="https://img.shields.io/github/languages/count/AbdallahHemdan/Wasla" />
<img src="https://img.shields.io/github/languages/top/AbdallahHemdan/Wasla" />
<img src="https://img.shields.io/github/languages/code-size/AbdallahHemdan/Wasla" />
<img src="https://img.shields.io/github/issues-pr-raw/AbdallahHemdan/Wasla" />


</div>

## About
> Wasla is a project to modulate three speech signals using the following scheme: `𝑠(𝑡) = 𝑥1(𝑡) cos 𝜔1𝑡 + 𝑥2(𝑡) cos 𝜔2𝑡 + 𝑥3(𝑡) sin 𝜔2𝑡`, and then perform synchronous demodulation

## Modulated signal

<div align='center'>

![image](https://user-images.githubusercontent.com/40190772/105381983-474aff80-5c18-11eb-8e0c-3d45454de366.png)
![image](https://user-images.githubusercontent.com/40190772/105381993-49ad5980-5c18-11eb-9b0c-a76dcfb6e8cc.png)

</div>


## Interference between modulated signals

- The Interference was between the low amplitude frequencies which has a very low impact into the final demodulated signals.
- The interference between the high amplitude frequencies was very low and the high amplitude frequencies have the most sound properties.
- So our final results didn't affected by the interference.

## <font color='008080'>Demodulated signals in (2) - (3)</font>

<div align='center'>

![image](https://user-images.githubusercontent.com/40190772/105381975-44e8a580-5c18-11eb-813b-6f3bf36b7345.png)

</div>

- The demodulated signals in (2) was as the original signal because of no shifting in phase (phi = 0)

- In (3), shifting by 10, 30 degrees attenuates the demodulated signals (speech signals) making them lower than the original ones.

- Shifting by 90 degree strongly attenuates the speech signals and it seems like no output speech.


### Contributors
<table>
  <tr>
    <td align="center"><a href="https://github.com/AbdallahHemdan"><img src="https://avatars1.githubusercontent.com/u/40190772?s=460&v=4" width="150px;" alt=""/><br /><sub><b>Abdallah Hemdan</b></sub></a><br /></td>
     <td align="center"><a href="https://github.com/AdelRizq"><img src="https://avatars2.githubusercontent.com/u/40351413?s=460&v=4" width="150px;" alt=""/><br /><sub><b>Adel Mohamed</b></sub></a><br /></td>
  </tr>
 </table>

### Licence
[MIT Licence](https://github.com/AbdallahHemdan/Wasla/blob/master/LICENSE)
