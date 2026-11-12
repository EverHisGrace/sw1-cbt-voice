# sw1-cbt-voice

「일급비밀」(사회복지사 1급 CBT) 앱의 읽어주기 음성 파일입니다.

- 원본 모델: [Supertone/supertonic-3](https://huggingface.co/Supertone/supertonic-3) (Supertone Inc.)
- 변경 사항: 용량을 줄이려고 ONNX 가중치를 fp16 으로 저장했습니다(불러올 때 fp32 로 되돌려 계산). 목소리 F1 만 포함합니다.
- 라이선스: 원본과 같은 **OpenRAIL-M** 라이선스를 따릅니다 — [LICENSE](LICENSE) 참고. 라이선스의 사용 제한(Attachment A)이 이 파일에도 그대로 적용됩니다.

파일은 [Releases](../../releases) 에 있습니다.
