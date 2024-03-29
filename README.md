# product_box_calculator
-------

## 설명
휴학하고 회사에서 아르바이트를 하던 중

제품을 포장하는데 제품별로 박스 당 제품 갯수가 달라 혼돈이 왔다.

간편하게 해결하기 위해 Python으로 간단하게 엑셀에서 Search 해 올 수 있는 프로그램을 만들어 보았다.

(회사 보안으로 인해 엑셀 파일은 임시로 제작한 것으로 대체했다.)

## 환경
<p align="center">
  <a href="https://www.spyder-ide.org/" target="_blank">
    <img src="img/Spyder.png" width="400" height="200"/>
  </a>
</p>
<p align="center">
  <a href="https://www.spyder-ide.org/" target="_blank">
    <img src="https://img.shields.io/badge/Spyder IDE Download-FF0000?style=flat-for-the-badge&logo=spyderide&logoColor=white"/>
  </a>
</p>

- tkinter
```
pip install tk
```
- PIL
```
pip install Pillow
```
- openpyxl
```
pip install openpyxl
```
- pyinstaller
```
pip install pyinstaller
```
- Making EXE file
```
pyinstaller --add-binary "path\\PIL;PIL" --add-binary "path\\openpyxl;openpyxl" -F -w --icon=아이콘명.ico 파일명.py
```

## 구현 사진
![1111](https://github.com/AF797/product_box_calculator/assets/86837707/7818ea0f-7ee9-4886-9e56-279029cbd1c7)

![2222](https://github.com/AF797/product_box_calculator/assets/86837707/143f111b-fc8e-4aab-832d-95cbd8ded49f)

![3333](https://github.com/AF797/product_box_calculator/assets/86837707/b84a3a79-2807-4d87-af69-ef7625d33d05)
![4444](https://github.com/AF797/product_box_calculator/assets/86837707/ee671d66-f7d3-4483-b707-b4e23a06e367)

## 최신 사진
![5555](https://github.com/AF797/product_box_calculator/assets/86837707/87fb490c-3a60-4452-9621-b0afaf9460de)

(수정날짜: 23.06.01)
