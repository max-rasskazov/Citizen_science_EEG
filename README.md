# Citizen_science_EEG
Проект по распознаванию эмоций по ЭЭГ. ВШЭ ФКН 3-курс

Первый этап

Дедлайн (примерно) (29 ноября или 6 декабря)

Цель: 

  Научиться работать с данными, установить необходимые библиотеки

Данные:

  https://yadi.sk/d/0PCqBPdk3KLMRa

Задание выполняются на язке питон

Мануал для того, чтобы начать:
  pip install mne
  import mne
  raw = mne.io.read_raw_brainvision("/data/resting_state/zavrin_open_eyes_eeg_15021500.vhdr")
  raw.get_data().shape
Дальше смотрим:
  http://martinos.org/mne/stable/auto_tutorials/plot_visualize_raw.html
  
 Удачи!
