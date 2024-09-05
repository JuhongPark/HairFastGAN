# Mirror Mirror GAN

Mirror Mirror GAN은 새로운 Hair Style을 체험해볼 수 있는 어플리케이션입니다

Image와 Text를 기반으로 나에게 어울리는 Hair를 체험해보세요.

아래 링크를 통해 Colab으로 연결된 Mirror Mirror GAN 어플리케이션을 체험해보실 수 있습니다.

본 어플리케이션은 [Hair Fast GAN](https://arxiv.org/abs/2404.01094)과 [Stable Diffusion](https://arxiv.org/abs/2112.10752)을 활용하여 개발되었습니다.

<span style="color:red">* Chrome 사용 권장 (Safari 웹 호환성 에러 발생) * </span>

## 1. Setting 방법

1. 아래 링크를 통해 Colab을 실행

    [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/JuhongPark/MirrorMirrorGAN/blob/app/app/MirrorMirrorGAN_Application.ipynb)

2. Model Load를 실행하여 Environment 설정 - T4 GPU 기준 12분 가량 소요

    <img src="https://i.postimg.cc/Vv4rGNsX/1.png" width="300"/>

## 2.1 Image 기반 Hair Style 생성 방법

1. `Face 사진 업로드` 실행 후, 하단에 생성된 `Face 사진 업로드` 버튼을 클릭하여 합성할 Face 사진 업로드 (사진 업로드시, 매번 실행해야함)

    <img src="https://i.postimg.cc/rw2XnNbC/3.png" width="300"/>

    * 결과

    <img src="https://i.postimg.cc/3xjMPDQM/4.png" width="300"/>

2. `Shape 사진 업로드` 실행 후, 하단에 생성된 `Shape 사진 업로드` 버튼을 클릭하여 합성할 Shape 사진 업로드 (1번과 동일)

3. `Color 사진 업로드` 실행 후, 하단에 생성된 `Color 사진 업로드` 버튼을 클릭하여 합성할 Color 사진 업로드 (1번과 동일)

4. `Hair 이미지 생성 - 옵션 메세지 입력`의 코드 실행

    <img src="https://i.postimg.cc/hGMkGWGp/5.png" width="300"/>


## 2.2 Text 기반 Hair Style 생성 방법

1. `Face 사진 업로드` 실행 후, 하단에 생성된 `Face 사진 업로드` 버튼을 클릭하여 합성할 Face 사진 업로드

    [(위의 Image 기반 Hair Style 생성 방법과 동일)](#21-image-기반-hair-style-생성-방법)

3. `Hair 이미지 생성 - 옵션 메세지 입력` 부분에 희망하는 Hair Shape의 Text 입력

4. `Hair 이미지 생성 - 옵션 메세지 입력` 부분에 희망하는 Hair Color의 Text 입력

5. `Hair 이미지 생성 - 옵션 메세지 입력`의 코드 실행