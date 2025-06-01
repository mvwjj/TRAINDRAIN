# PingPong team

Představujeme vám nejlepší VR online realtime tahovou strategii - PingPong.

## Členové týmu

* velká pálka <velka@palka.ctu.cz>
* malá pálka <mala@palka.ctu.cz>

## INFO - Jak nakládat s tímto repositářem
1. Zachovejte strukturu: 
    1. `tvs_documentation, tvs_submission` - **NEMAZAT**, nepřejmenovávat
    2. `tvs_project_rename` - můžete přejmenovat, mělo by to odpovídat vašemu názvu VR projektu
        - Hlavní adresář s UE5 projektem by tedy měl být `tvs_project_rename`, který si pak na něco přejmenujete
        - Adresář NEMAŽTE - jen přejmenujte - jsou tam soubory pro vhodné nastavení gitu pro UE5 (`.gitattributes`, `.gitignore`    )
        - Jména adresáře nezapomeňte změnit v `tvs_project.json`
2. V `master` větvi by měla být vždy zkompilovatelná, pokud možno co nejkompletnější, hra. Využívejte proto větvení (*branches*), které git nabízí a vývojové verze si držte v druhotných větvích, např. @devel.
4. Je potřeba si zapnout git-lfs - více **[ZDE](./README.git.md)**
5. Upravte **[tvs_project.json](./tvs_project.json)** !!!

## něco málo navíc ##
- pro formátování textu na GIT-labu a připojené wiki se používá [markdown](https://guides.github.com/features/mastering-markdown/#what) syntaxe, a [zde](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) jsou další pokročilé příklady, jako tabulky
- velmi užitečný odkaz pro začínající s Gitem - https://nvie.com/posts/a-successful-git-branching-model/
