# Fixa LAN-anslutning (Windows 10)
För att kunna ansluta till lokala prov, måste din nätverksprofil vara inställd på "Privat", inte "Offentligt". 
Är du ansluten via Wi-Fi går du till ditt nätverk och klicka på "Egenskaper" och sedan "Privat". Se nedan.

![1](https://user-images.githubusercontent.com/90912016/171602308-d3271909-8c24-4c38-a801-2bb84e6e4cb2.png)

![2](https://user-images.githubusercontent.com/90912016/171602327-83353f06-2cbc-432d-a925-298b814204f2.png)

## Brandväggen
Om LAN fortfarande inte fungerar, kan det bero på Windows Defender-brandväggen. Öppna dess inställningar genom att t.ex. skriva "brandvägg" i aktivitetsfältets sökfält och välj "Windows Defender-brandväggen". Klicka sedan på "Tillåt en app...". Du kan behöva klicka på "Ändra inställningar" i nästa steg om du inte kan ändra något. Sedan scrollar du ner tills du ser grejer som heter "Godot Engine". Ta bort dem. Klicka sedan på "OK". Nu när du startar Teknikquiz på nytt bör rutan med brandväggen dyka upp igen. Kryssa då för båda rutorna. Se nedan.

![1](https://user-images.githubusercontent.com/90912016/189974279-8b1e08ca-810b-490d-8619-b1a4cece568e.png)

![2](https://user-images.githubusercontent.com/90912016/189974294-a7b35033-98fb-4e07-afd4-ca9d93bf5068.png)
