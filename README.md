# Research Project : Revealing neural mechanisms of repetition suppression using a voxel-wise background connectivity analysis

## Index
  - [Authors](#authors) 
  - [About](#about) 
  - [Overview](#overview) 
  - [Files](#files)
  - [License](#license)

## Authors
- **Taehoon Kim**, & Ghootae Kim
- Deep Memory Lab, Cognitive Science Research Group, Korea Brain Research Institute

## About
- 이 Repository는 KBRI, 인지과학 연구그룹, 심층기억연구실에서 2020에 수행한 fMRI 인지 실험의 데이터 분석 작업물 초안을 담고 있습니다.
- 실험 프로그램와 fMRI 영상 데이터 전처리 등을 위한 코드, 개별 참가자의 원본 데이터는 포함되어 있지 않습니다. 
- 분석은 R과 R studio를 통해 수행되었으며, 분석 코드 및 결과는 **repSup_results.html** 를 다운로드받아서 확인할 수 있습니다. 
- 다른 파일에 대한 정보는 아래 **FILES**에서 확인할 수 있습니다.

## Overview
- 반복에 의한 신경 활성화(fMRI BOLD signal)의 감소, Repetition Suppression (또는 fMR adaptation)의 신경 메커니즘에 관한 분석
- Suppressed Voxel, Enhanced Voxel 의 역할? Suppression은 불필요한 신경 활성화의 가지치기(sharpening model)인가 error signal의 감소(predictive coding model)인가를 확인
- Suppressed Voxel & Enhanced Voxel과 상위 영역 간 background connectivity analysis 수행. 어느 복셀이 더 높은 연결성을 가지는지 확인.
- Suppressed Voxel이 상위 영역과 background connectivity 가 더 높은 것을 확인.

## Files
- repSup_results.Rmd : 데이터 분석을 위한 RMarkDown source code
- repSup_results.html : 분석 코드 및 결과, 다운로드 후 확인 가능
- data : raw data 폴더, 비어있음

## License

```
MIT License

Copyright (c) 2020 Kim, Taehoon

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

```
