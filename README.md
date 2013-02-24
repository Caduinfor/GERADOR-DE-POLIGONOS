GERADOR-DE-POLIGONOS ==
====================

Gerador de polígonos para representação de Contornos de Propagação para Radiodifusão com plotagem em sistema GIS do Google Earth
   
Resumo: Este trabalho visa promover maior qualidade técnica contribuindo para o estudo e a viabilidade de propagação para radiodifusão. Para tal foi necessário o desenvolvimento de um sistema capaz de gerar polígonos que representam a cobertura do alcance de propagação do sinal transmitido por uma antena. O sistema em questão utiliza um algoritmo baseado na formula inversa de Vincenty para calcular os pontos do alcance máximo do sinal, a partir do ângulo (Azimute) e distância fornecidos, tendo em vista as linhas geodésicas no elipsóide de revolução. Foi utilizado para a implementação do sistema gerador a linguagem Ruby, dinâmica, open source com foco na simplicidade e na produtividade, com uma sintaxe elegante de leitura natural e fácil escrita. Os dados inseridos no programa são fornecidos pela Agência Nacional de Telecomunicações (ANATEL) de acordo com as normas e os regulamentos técnicos para a prestação dos serviços de radiodifusão de sons e imagens. Por fim, o tratamento computacional dos dados dos contornos 
obtidos é plotado no sistema GIS do Google Earth.
