+++
menus = [
    { content = "Home", title = "home", href = "#home" },
    { content = "Blog", title = "blog", href = "/blog" },
    { content = "Sobre", title = "sobre", href = "#sobre" },
]

[extra.profile]
title = "Eu sou Paulo A"
description = """Desenvolvedor baseado em desafios"""
buttons = [
    { text = "Blog", url = "#blog" },
    { text = "Sobre Mim", url = "#sobre" },
]
arrow = "Conheça-me"

[extra.about]
title = "Sobre"
description = ""
content = """
Trabalho como desenvolvedor em diversas áreas. Já trabalhei com muitas tecnologias em várias linguagens diferentes também, seja backend, frontend, mobile, data science e machine learning. Cada uma dessas áreas utilizou o que parecia mais adequado ao problema. Atualmente, tenho trabalhado mais com flutter, rust, typescript e python. Depois de muitos anos na área, acredito que uma habilidade importante é aprender sob demanda e ser capaz de se adaptar.
"""
extra = """
No meu blog você pode acompanhar minha prática de \"aprender em público\" e também sobre temas que gosto.
"""

[extra.about.more]
title = "Curriculum Vitae"
content = "Sou formado em engenharia da computação. Minha experiência em empresas é em áreas como backend (laravel - php), desenvolvimento mobile nativo (android - kotlin, ios - swift) e data science/machine learning (python). Tenho outras habilidades, algumas destacadas: desenvolvimento usando typescript (node, react), mobile com flutter. Iniciei um mestrado na área de Biologia Molecular Computacional, mas não o terminei devido à covid-19."
button = "Veja meu Currículo"
button_href = "cv.pdf"

[extra.skills]
enabled = true
skills_title = "Tecnologias que utilizo/estudo atualmente"
skills = [
    { name = "Python", percentage = "90" },
    { name = "HTML5, CSS3, JS e Web clássico", percentage = "90" },
    { name = "PHP Nativo e Laravel", percentage = "90" },
    { name = "React e React Native", percentage = "85" },
]

[extra.timeline]
enabled = true
title = "Experience"
left = [
    { period = "2020 - ", place = "Somewhere", work = "Developer", content = """Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui corrupti, dolore quia exercitationem doloremque ex consequuntur quasi eos vitae molestiae recusandae similique expedita illo sapiente nisi ipsam! Fugiat, distinctio saepe?""" },
    { period = "2020 - ", place = "Somewhere", work = "Developer", content = """Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui corrupti, dolore quia exercitationem doloremque ex consequuntur quasi eos vitae molestiae recusandae similique expedita illo sapiente nisi ipsam! Fugiat, distinctio saepe?""" }
]

right = [
    { period = "2020 - ", place = "Somewhere", work = "Developer", content = """Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui corrupti, dolore quia exercitationem doloremque ex consequuntur quasi eos vitae molestiae recusandae similique expedita illo sapiente nisi ipsam! Fugiat, distinctio saepe?""" },
    { period = "2020 - ", place = "Somewhere", work = "Developer", content = """Lorem ipsum, dolor sit amet consectetur adipisicing elit. Qui corrupti, dolore quia exercitationem doloremque ex consequuntur quasi eos vitae molestiae recusandae similique expedita illo sapiente nisi ipsam! Fugiat, distinctio saepe?""" }
]

[extra.projects]
enabled = true
title = "Projetos"
description = "Alguns projetos pessoais"
content = """Aqui estão alguns dos mais recentes projetos pessoais. Projetos desenvolvidos em empresas não podem ser listados por serem sistemas em produção."""
projects = [
    { image = "https://picsum.photos/500/300", title = "Um projeto", subtitle = "Uma descrição", href = "#", text = "" },
    { image = "https://picsum.photos/500/300", title = "Um projeto", subtitle = "Uma descrição", href = "#", text = "" },
    { image = "https://picsum.photos/500/300", title = "Um projeto", subtitle = "Uma descrição", href = "#", text = "" },
    { image = "https://picsum.photos/500/300", title = "Um projeto", subtitle = "Uma descrição", href = "#", text = "" },
]

[extra.quote]
enabled = true
text = "\"Se as coisas não estão falhando, você não está inovando o suficiente\""
author = "Elon Musk"

[extra.github]
enabled = true
username = "pauloasjx"
global_stats = true

[extra.contact]
enabled = true
title = "Contato"
description = "Você pode entrar em contato"
content = """Se tiver interesse em discutir sobre inteligência artificial ou problemas de computação no geral. Será um prazer trocar uma ideia."""
+++