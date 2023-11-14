# Trabalho de Conclusão de Curso (TCC)

## Introdução
Desde a criação do primeiro computador, o Eniac em 1946 (WEIK, 1961), até os dias atuais, a área de hardware e software passou por diversos avanços significativos. Uma demonstração desse progresso é a evolução na área de testes de software, não apenas para aplicações, mas também para ferramentas que auxiliam os desenvolvedores, como compiladores, Integrated Development Environments (IDEs), Application Programming Interfaces (APIs), etc.

Com o tempo, tornou-se evidente que testes manuais por si só não são suficientes para garantir a qualidade do software, especialmente em relação às ferramentas de desenvolvimento, que precisam ser robustas em diversos cenários. A linguagem Java, sendo orientada a objetos, fortemente tipada e amplamente utilizada desde 1995 (CLARO; SOBRAL, 2008), oferece uma variedade de ferramentas que facilitam o desenvolvimento.

## Desenvolvimento em Java
As IDEs Java fornecem recursos valiosos, como destaque de sintaxe, auto-completar código e refatoração automática. A refatoração automática atua na sugestão ou alteração de código de forma automática, facilitando a produção de códigos mais simples, legíveis e modernos sem alterar a semântica inicialmente descrita pelo desenvolvedor. No entanto, como qualquer artefato de software, os mecanismos de refatoração podem conter ou introduzir bugs, exigindo um rigoroso controle de qualidade.

## Testes e Qualidade do Software
A área de pesquisa em testes de sistemas tem evoluído, proporcionando ferramentas para aprimorar a confiabilidade do sistema. Testes unitários e testes baseados em propriedades são exemplos comuns. Este projeto se concentra na última abordagem, utilizando código gerado aleatoriamente para criar casos de teste capazes de testar os mecanismos de refatoração automática da linguagem Java.

Durante um projeto de Iniciação Científica no IFSC, foi desenvolvido um gerador de código Java (KRAUS et al., 2021) que utiliza Java Reflection, JavaParser e JQWik para gerar construções básicas da linguagem e executar testes com propriedades definidas.

## Metodologia
Neste projeto, utilizamos o gerador de código Java para criar centenas de programas válidos, gerando casos de teste compilados com o compilador da Oracle, Java versão 18, através da IDE NetBeans. Em seguida, aplicamos as refatorações de rename, invert conditions e Move Class em cada caso de teste, verificando se o código refatorado mantinha a propriedade de compilação (compilation preservation).

Este trabalho visa contribuir para a melhoria da qualidade do software, especialmente nas ferramentas de desenvolvimento Java, ao proporcionar uma abordagem sistemática para testar os mecanismos de refatoração automática.

## Conclusão
Ao explorar a geração de casos de teste baseados em propriedades para testar os mecanismos de refatoração automática em Java, este trabalho contribui para a compreensão e aprimoramento da qualidade do software. Os resultados obtidos na aplicação das refatorações em programas gerados aleatoriamente fornecem insights valiosos sobre a eficácia e confiabilidade desses mecanismos.

Espera-se que este trabalho incentive futuras pesquisas na área de testes de software e forneça uma base sólida para o aprimoramento contínuo das ferramentas de desenvolvimento Java.
