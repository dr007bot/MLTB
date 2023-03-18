## Usage

- ဒီrepo ကို forkပါ. Fork or Import this repo.
- Fill req vars at config.env တွင် မဖြစ်မနေဖြည့်ရမည့် vars များဖြည့်ပါ
- koyeb, render, railway တွင် Deploy ပါ။ 

## RenderDeploy

- Render ဖွင့်ပြီး free signup လုပ်ပါ။
- dashboard.render.com ဖွင့်ပြီး new + ကို နှိပ် web service ကို ရွေးပါ
- Public Git repository နေရာတွင် သင့် repo or your fork repoထည့်ပါ။
- name နေရာ ကြိုက်ရာထားပါ
- advanced မှ docker *auto deploy* ကို **NO** ပြောင်းပါ
- ပြီးလျှင် အောက်ဆုံးနားက create web service အပြာရောင် ကို နှိပ်ပြီး ခဏေစာင့်ပါ
- terminal box တက်လာပြီး install ပါမည်။ Bot Start စာပေါ်လာလျှင် စသုံးလို့ရပါပြီ။
- Bot run လျှင် app url ကို cronjob တွင် connect ပါ

## Deploy on Koyeb

- at koyeb deploy, choose docker image
- fill as name **npt13/mltbr**
- tag **16.3.23**
- add CONFIG_FILE_URL at Env Vars (must be set Base Url, Port)
- ♦♦addition FILL Koyeb Exposing your Service port to 80
- and deploy
