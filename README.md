# TRAINDRAIN team

TRY TO RIDE THE TRAIN AS FAR AS POSSIBLE. KILL THEM MONSTERS AND TRY TO SURVIVE.


## Členové týmu

* Zaikin Volodymir zaikivol@fel.cvut.cz
* Zhidkov Aleksandr zhidkale@student.cvut.cz


## INFO - Jak nakládat s tímto repositářem
1. Zachovejte strukturu: 
    1. `var_reports, var_submission, var_AR_projects, var_3D_models` - **NEMAZAT**, nepřejmenovávat
    2. `var_project` - můžete přejmenovat, mělo by to odpovídat vašemu názvu VR projektu
        - Hlavní adresář s unity projektem by tedy měl být `var_project`, který si pak na něco přejmenujete
    3. v  [var_AR_projects](./var_ar_projects), [var_3D_models](./var_3D_models) vytvoříte podsložky pro jednotlivé uživatele
2. V `master` větvi by měl být vždy zkompilovatelný, pokud možno co nejkompletnější, VR projekt. Využívejte proto větvení (*branches*), které git nabízí a vývojové verze si držte v druhotných větvích, např. @devel.
3. Označujte reporty a milníky pomocí **tagů** (report1, milestone4, ...), aby bylo vidět, k jakému bodu se daný milník/report vztahuje.
4. Je potřeba si zapnout git-lfs - více **[ZDE](./var_project/README.md)**
5. Z této stránky smažte toto info - nebo si jej někam zkopírujte

## něco málo navíc ##
- pro formátování textu na GIT-labu a připojené wiki se používá [markdown](https://guides.github.com/features/mastering-markdown/#what) syntaxe, a [zde](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) jsou další pokročilé příklady, jako tabulky
- velmi užitečný odkaz pro začínající s Gitem - https://nvie.com/posts/a-successful-git-branching-model/
