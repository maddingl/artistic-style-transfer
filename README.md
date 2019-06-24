# Artificial Art with more than one style image

In diesem Projekt wollen wir uns mit dem Erstellen von Bildern aus Content- und Style- Bildern mithilfe von maschinellem Lernen beschäftigen. 

Als Grundlage dieser Arbeit dient [dieses Notebook von Harish Narayanan](https://github.com/hnarayanan/artistic-style-transfer/blob/master/notebooks/6_Artistic_style_transfer_with_a_repurposed_VGG_Net_16.ipynb).
Wir erweitern dieses um unsere eigenen Gedanken, und führen die Option ein, mehrere Style- Bilder zu verwenden. Am Ende zeigen wir unsere eigenen Bilder und welchen Einfluss die verschiedenen Parameter haben.

Der Inhalt weicht von dem ursprünglich geplanten Inhalt, der im Exposé beschrieben war, ab. 
Wir fanden das genannte Notebook geeigneter, um die Zusammenhänge zu analysieren.

# Installation Instructions:

```
git clone git@github.com:maddingl/artistic-style-transfer.git
cd artistic-style-transfer
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
ipython kernel install --user --name=artistic-style-transfer
```

afterwards you can start jupyter notebook or jupyter lab and use the kernel named "artistic-style-transfer"
