Fazer um mapa mental

Entidade Certificadora --> 
                        Certificado Digital 
                                        --> Assinatura digital                    Simétrica
                                                            --> Criptografia -->  
                                                                                  Assimétrica
                                                                                            --> Chave Publica & Privada


# Entidade Certificadora

Uma **Entidade Certificadora**, também conhecida como **Autoridade Certificadora (AC)**, é uma organização responsável por emitir e gerenciar certificados digitais. Essas entidades têm a função de garantir a autenticidade e a validade dos certificados que emitem, certificando que a chave pública presente no certificado digital pertence realmente ao titular. 

Aqui estão os principais pontos sobre uma **Entidade Certificadora**:

1. **Emissão de Certificados**: A principal função da Autoridade Certificadora é emitir certificados digitais para indivíduos, empresas, ou sistemas. Para isso, ela valida a identidade do solicitante por meio de documentos e outros processos de verificação.

2. **Garantia de Autenticidade**: Ao emitir um certificado digital, a Autoridade Certificadora garante que a chave pública contida no certificado pertence realmente à pessoa ou entidade que solicitou o certificado. Isso assegura que as comunicações e transações feitas com o certificado são autênticas.

3. **Hierarquia de Confiança**: As Autoridades Certificadoras são parte de uma **Infraestrutura de Chaves Públicas (ICP)**. No Brasil, por exemplo, a ICP-Brasil é a entidade responsável por gerenciar a infraestrutura de certificados digitais do país. ACs fazem parte de uma hierarquia, onde as **Autoridades Certificadoras Raiz** são o topo da cadeia, responsáveis por certificar outras Autoridades Certificadoras Subordinadas.

4. **Revogação de Certificados**: As ACs também têm a responsabilidade de revogar certificados digitais, caso seja detectado algum comprometimento de segurança, ou quando o titular solicita a revogação.

5. **Segurança e Confiabilidade**: As Autoridades Certificadoras seguem rigorosos padrões de segurança para assegurar que a emissão e o gerenciamento dos certificados digitais sejam confiáveis. Elas utilizam tecnologias de criptografia para garantir a integridade e a confidencialidade das informações.

Alguns exemplos de **Autoridades Certificadoras** no Brasil são:
- Serpro
- Certisign
- SERASA Experian
- Safeweb


# Certificado:

Um **certificado digital** é um documento eletrônico que serve como uma identidade virtual, garantindo a autenticidade e a segurança de transações e comunicações digitais. Ele funciona de maneira semelhante a um documento de identidade físico, como um RG ou passaporte, mas é utilizado em ambientes virtuais.

Aqui estão os principais aspectos do certificado digital:

1. **Autenticação**: Permite que uma pessoa ou empresa comprove sua identidade no meio eletrônico. Isso é importante para garantir que a comunicação ou transação está sendo feita por quem realmente diz ser.

2. **Assinatura digital**: O certificado digital possibilita a criação de uma assinatura digital, que tem o mesmo valor jurídico de uma assinatura manuscrita, garantindo a integridade dos documentos e a autenticidade de quem os assinou.

3. **Criptografia**: Utiliza algoritmos criptográficos para proteger dados e comunicações, garantindo que eles não sejam alterados ou acessados por terceiros durante o tráfego pela internet.

4. **Emissão**: Um certificado digital é emitido por uma **Autoridade Certificadora (AC)**, que é uma entidade confiável, responsável por validar a identidade de quem está solicitando o certificado.

5. **Validade jurídica**: No Brasil, a Infraestrutura de Chaves Públicas Brasileira (ICP-Brasil) regulamenta o uso de certificados digitais, conferindo validade jurídica a documentos assinados digitalmente.

Os certificados digitais são amplamente usados em diferentes áreas, como para acessar sistemas de governo (e-CAC, eSocial), realizar transações bancárias, emitir notas fiscais eletrônicas e assinar contratos digitais.


A **assinatura digital** é uma forma de autenticação eletrônica que garante a integridade e a autenticidade de um documento ou transação digital. Ela tem a mesma função de uma assinatura manuscrita em documentos físicos, mas é usada no ambiente eletrônico, sendo mais segura devido ao uso de criptografia. No Brasil, a assinatura digital possui validade jurídica, desde que emitida com base em um certificado digital no âmbito da **Infraestrutura de Chaves Públicas Brasileira (ICP-Brasil)**.

### Características principais da assinatura digital:

1. **Autenticidade**: A assinatura digital confirma a identidade do signatário, ou seja, a pessoa que assinou o documento. Ela é associada a um certificado digital, emitido por uma **Autoridade Certificadora (AC)**, que garante que o signatário é realmente quem ele diz ser.

2. **Integridade**: A assinatura digital assegura que o conteúdo do documento não foi alterado após a assinatura. Se alguém tentar modificar o documento, a assinatura digital será invalidada, alertando sobre a mudança.

3. **Irretratabilidade**: O autor de uma assinatura digital não pode negar que assinou o documento (não repúdio). Isso dá segurança jurídica, pois a assinatura digital tem validade legal, desde que emitida por uma entidade da ICP-Brasil.

4. **Criptografia**: A assinatura digital utiliza criptografia de chave pública. Quando alguém assina digitalmente, o sistema gera duas chaves:
   - **Chave privada**: Exclusiva do signatário e usada para assinar o documento.
   - **Chave pública**: Disponível para todos e usada para verificar a autenticidade da assinatura.

5. **Validade Jurídica**: No Brasil, a Lei nº 14.063/2020 regulamenta a validade das assinaturas digitais, garantindo que documentos eletrônicos assinados com um certificado digital emitido pela ICP-Brasil tenham a mesma validade de um documento assinado manualmente.

### Como funciona uma assinatura digital:
- O signatário usa sua **chave privada** (armazenada em um certificado digital) para criar a assinatura digital de um documento.
- Essa assinatura gera um código único que fica vinculado ao documento.
- Quem recebe o documento pode usar a **chave pública** do signatário para verificar se a assinatura é válida e se o conteúdo não foi alterado.

### Exemplos de uso:
- **Contratos eletrônicos**: Assinatura digital garante que ambas as partes assinaram um contrato de forma segura.
- **Nota Fiscal Eletrônica (NF-e)**: Empresas usam assinaturas digitais para validar e emitir notas fiscais eletrônicas.
- **Declarações e processos judiciais**: Advogados e empresas podem assinar petições e documentos de forma digital.
- **Assinaturas de e-mails**: Garantem que o conteúdo de um e-mail não foi alterado e que ele realmente veio do remetente informado.

### Tipos de assinaturas eletrônicas no Brasil:
Além da assinatura digital (que requer um certificado digital), existem outros tipos de assinaturas eletrônicas:
- **Assinatura eletrônica simples**: Não envolve certificado digital, sendo mais usada em situações de menor risco.
- **Assinatura eletrônica avançada**: Utiliza métodos que associam a assinatura ao signatário, mas não necessariamente com um certificado da ICP-Brasil.

A **assinatura digital** é amplamente utilizada em ambientes corporativos, governamentais, jurídicos e financeiros, onde a segurança, autenticidade e validade jurídica são fundamentais.