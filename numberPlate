import cv2
import pytesseract

pytesseract.pytesseract.tesseract_cmd=r'tesseract.exe'

img=cv2.imread('numberplate.png')
text=pytesseract.image_to_string(img)
print(text)
