Change Log
---

### v1.0.6 (2018-09-05)

* Be going to deprecate the "i18n" option. (:> �ui18n�v�I�v�V�����͔p�~�\��ɂȂ�܂����B
* Added the "getLangUrl" option; Enabled when httpLanguage is TRUE, an option to get the value of the Accept-Language header from the specified URL and set it to the plug-in's current language. An example code of returning value from the designated URL is presented separately. (:> getLangUrl �I�v�V������ǉ� : httpLanguage �� TRUE �̏ꍇ�ɗL���ɂȂ�A�w���URL���� Accept-Language �w�b�_�̒l���擾���A�v���O�C���̃J�����g����ɃZ�b�g���邽�߂̃I�v�V�����B�w��URL����̖߂�l�̃T���v���R�[�h�͕ʓr�񎦂���B
* Added "duration" option; You can set the animation time of the transition effect such as movement of the timeline and adjustment at event selection. The initial value is 150 milliseconds, and it can be specified as a millisecond number or preset string of "fast", "normal", "slow". (:> duration �I�v�V������ǉ� :  �^�C�����C���̈ړ���A�C�x���g�I�����̃A�W���X�g�����̃g�����W�V�������ʂ̃A�j���[�V�������Ԃ�ݒ�ł���B�����l�� `150` �~���b�ŁA�~���b�̐��l�� `fast` `normal` `slow` �̃v���Z�b�g������ł̎w�肪�\�B
* Implemented the debug mode; If you set "debugMode" (currently constant) to TRUE, output of various logs for debugging and wait processing at initialization become effective. (:> �f�o�b�O���[�h������ : debugMode �i���͂܂��萔�j�� TRUE �ɂ���ƃf�o�b�O�p�̊e�탍�O�̏o�͂⏉�������̃E�F�C�g�������L���ɂȂ�B

