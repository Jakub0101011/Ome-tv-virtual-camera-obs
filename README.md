# Tutorial Virtual Camera OBS 📺
## 1. First install [OBS Studio](https://obsproject.com/)
## 2. Now turn on Reg. Edit (Registry Editor)
![obraz](https://user-images.githubusercontent.com/94227436/197977129-55b3ed62-9bc7-4092-9d0f-8ca95336e55a.png)

## 3. Copy code 1 at the bottom and paste it in Reg Edit (do not delete: `Computer\`)
![obraz](https://user-images.githubusercontent.com/94227436/197977290-bb3e8c65-1980-4e8b-b438-0fe8d4a5a477.png)

## 3.2 Now Double click on "FriendlyName" and change it to "HD Webcam C290"
![obraz](https://user-images.githubusercontent.com/94227436/197979741-1bebf6c3-a839-4a94-a8e8-f4d7972e8b47.png)

## 4. Now copy code 2 at the bottom and do the same as for section 3.2
![obraz](https://user-images.githubusercontent.com/94227436/197977983-dfa5f3bf-2402-4d47-a080-060dccfae888.png)
![obraz](https://user-images.githubusercontent.com/94227436/197979881-2b102650-3d03-494c-b557-b8dc72c40a37.png)

## 5. Now Close Reg Edit and Open OBS Studio
## 6. Start OBS Virtual Camera and Open your browser
![obraz](https://user-images.githubusercontent.com/94227436/197978704-e56c8aff-628d-4dc6-8743-472c6f87ac07.png)
## 7. Now in the browser settings, search for the camera


## 8. Now Change Browser Webcam to HD Webcam C290
![obraz](https://user-images.githubusercontent.com/94227436/197979171-4080e090-a381-4eb5-b36d-3ab22a04bc32.png)

## 9. That is all !
>⚡ PS. if something doesn't work, you probably need to reset your computer

## Code 1
```
HKEY_LOCAL_MACHINE\SOFTWARE\WOW6432Node\Classes\CLSID\{860BB310-5D01-11d0-BD3B-00A0C911CE86}\Instance\{A3FCE0F5-3493-419F-958A-ABA1250EC20B}
```

## Code 2
```
HKEY_LOCAL_MACHINE\SOFTWARE\Classes\CLSID\{860BB310-5D01-11d0-BD3B-00A0C911CE86}\Instance\{A3FCE0F5-3493-419F-958A-ABA1250EC20B}
```
