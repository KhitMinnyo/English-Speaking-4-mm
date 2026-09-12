# Audio & Listening Library

ဒီ folder တွင် Level 1–3 Unit ၃၆ ခုအတွက် printable/listenable scripts ရှိသည်။ Audio binary မလိုတော့ပါ — **ChatGPT/Gemini (voice mode) သို့မဟုတ် ဖုန်း TTS** က script ကို **Slow 0.75x** နှင့် **Natural 1.0x** ဖတ်/ဖွင့်ပေးနိုင်သည် (partner/teacher မလို)။ Level 4 listening texts သည် Unit ဖိုင်တစ်ခုစီအတွင်း ပါရှိသည်။

**AI-first (v2):** ဖတ်ခိုင်းရန် prompt — “Read the script below aloud. First at slow/clear 0.75x, then at natural 1.0x. Do not show or summarize the text while I listen.” Prompt အပြည့်အစုံ: [`../AI-Chat-Prompt-Library.md`](../AI-Chat-Prompt-Library.md)။

## အသုံးပြုပုံ
1. Transcript မကြည့်ဘဲ slow version နားထောင်ပြီး gist ပြောပါ။
2. Natural version နားထောင်ပြီး details ဖြေပါ။
3. Transcript စစ်ပြီး unknown chunks mark လုပ်ပါ။
4. Sentence-by-sentence shadow ၃ ကြိမ်၊ နောက်ဆုံးတစ်ကြိမ် transcript ပိတ်ပါ။
5. Speaker role ပြောင်းပြီး personalized version record လုပ်ပါ။

## Audio ဖန်တီးရန်
- macOS: `say -r 135 -f script.txt -o slow.aiff` နှင့် `say -r 185 -f script.txt -o natural.aiff`
- အခြား TTS app တွင် neutral English voice ရွေးပြီး 0.75x/1.0x သုံးပါ။
- Voice တစ်မျိုးတည်းမစွဲစေရန် speaker/accent မျိုးစုံကို တဖြည်းဖြည်းထည့်ပါ။

> TTS သည် convenience tool သာဖြစ်သည်။ Pilot မထုတ်မီ naturalness, pauses, names နှင့် pronunciation ကို လူဖြင့်စစ်ဆေးပါ။
