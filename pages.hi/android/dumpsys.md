# dumpsys

> एंड्रॉइड सिस्टम सेवाओं के बारे में जानकारी प्रदान करें।
> इस कमांड का उपयोग केवल `adb shell` के माध्यम से किया जा सकता है।
> अधिक जानकारी: <https://developer.android.com/studio/command-line/dumpsys>.

- सभी सिस्टम सेवाओं के लिए नैदानिक आउटपुट प्राप्त करें:

`dumpsys`

- किसी विशिष्ट सिस्टम सेवा के लिए नैदानिक आउटपुट प्राप्त करें:

`dumpsys {{सेवा}}`

- उन सभी सेवाओं की सूची बनाएं जिनके बारे में `dumpsys` जानकारी दे सकता है:

`dumpsys -l`

- किसी सेवा के लिए सेवा-विशिष्ट तर्कों की सूची बनाएं:

`dumpsys {{सेवा}} -h`

- नैदानिक आउटपुट से एक विशिष्ट सेवा को बाहर करें:

`dumpsys --skip {{सेवा}}`

- सेकंड में टाइमआउट अवधि निर्दिष्ट करें (डिफ़ॉल्ट 10s पर):

`dumpsys -t {{8}}`
