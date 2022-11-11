# iOS_Basic
iOS 앱 제작 SWIFT프로그래밍 입문_주말


2022-11-12 ~ 2022-12-17

연락처 : kennysy@naver.com


Zoom 연결 : 
    https://us02web.zoom.us/j/6962261155?pwd=WWZsSDFQZ3ZsU2tndzg4Z0FybGZpUT09


*Swift

    // 아무곳이나 눌러 softkeyboard 지우기
    override func touchesBegan(_ touches: Set<UITouch>, with event: UIEvent?) {
        self.view.endEditing(true)
    }
