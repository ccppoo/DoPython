# Pickle - 파이썬 객체를 바이너리로

파이썬에서 리스트(list)를 생성하면 그 자체 데이터는 주 메모리(RAM)에 저장되어 있는 상태를 의미합니다.

그림(png, jpg), 텍스트(txt)와 같은 일반 파일이 아닌 임시로 저장된 바이트에 불과합니다.

이런 임시로 저장된 바이트들을 파일로 저장하려면 시리얼라이징(serializing) 과정이 필요하고

파이썬 객체를 저장할 수 있겠끔 해주는 것이 pickle 모듈입니다.