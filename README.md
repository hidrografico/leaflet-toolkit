# 🗺️ _leaflet-toolkit_

![github](https://img.shields.io/github/stars/institutohidrografico/leaflet-toolkit "Github")
[![GitHub stars](https://img.shields.io/github/stars/hidrografico/leaflet-toolkit?style=social)](https://github.com/hidrografico/leaflet-toolkit)
[![GitHub forks](https://img.shields.io/github/forks/hidrografico/leaflet-toolkit?style=social)](https://github.com/hidrografico/leaflet-toolkit/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/hidrografico/leaflet-toolkit?style=social)](https://github.com/hidrografico/leaflet-toolkit)

![GitHub last commit](https://img.shields.io/github/last-commit/gadelhati/maps-back)
![Test Coverage](https://img.shields.io/badge/coverage-5%25-orange)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen)
![Code Quality](https://img.shields.io/badge/code%20quality-A-brightgreen)

## **Necessary Tech stack**

![Node.js](https://img.shields.io/badge/Node.js-22.20.0-339933?logo=node.js)
![npm](https://img.shields.io/badge/npm-11.6.2-CB3837?logo=npm)
![Vite](https://img.shields.io/badge/Vite-5.3.10-646CFF?logo=vite)
![React](https://img.shields.io/badge/React-19.2.0-blue?logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5.9.3-blue?logo=typescript)

## Description

A versatile toolkit for **geospatial data visualization and analysis**, designed to support real-time monitoring, decision-making, and interdisciplinary applications.  
Perfect for **maritime operations, hydrographic surveys, nautical charts, ship tracking, and marine navigation systems**.

### Necessary Tech stack:

|Name                 | Source | File name version		      |Link for download
|:-------------------:|-------:|---------------------------:|:-----------------
|`typescript`         |language|                            |https://www.typescriptlang.org/
|`node`			          | engine |node-v22.20.0-x64.msi			  |https://nodejs.org/en/download
|`visual studio code` |  IDE   |VSCodeUserSetup-x64-1.105.0	|https://code.visualstudio.com/docs

## 🌊 About Instituto Hidrográfico

Developed by the **_Instituto Hidrográfico_** for advancing maritime research, hydrographic surveying, and oceanographic studies. This toolkit supports our mission to enhance marine navigation safety and promote sustainable ocean use.

![Alt Print 000](https://github.com/institutohidrografico/leaflet-toolkit/blob/main/src/image/print.png "Print 000")

## Sumary
* [Quick start](#quick-start)
* [Development](#development)
* [Roadmap](#roadmap)
* [Developer setup](#developer-setup)
* [Git setup for developer](#git-setup-for-developer)
* [Contributing](#contributing)
* [Developers](#developers)
* [Licence](#licence)

## Quick start
Installation
```bash
npm install @institutohidrografico/leaflet-toolkit
```
basic usage
```javascript
import { MapComponent } from '@institutohidrografico/leaflet-toolkit';

function App() {
  return (
	<Map />
  );
}
```

## Development
### Setup
```bash
# clone the repository
git clone https://github.com/institutohidrografico/leaflet-toolkit.git
cd leaflet-toolkit

# install dependencies
npm install

# build the library
npm run build
```

### Build
```bash
npm run build
```

### Publish
to npm Registry
```bash
# login to npm (first time only)
npm login

# build and publish
npm run build
npm publish --access public
```

to GitHub Packages, create a .npmrc file in your project root:
```text
@institutohidrografico:registry=https://npm.pkg.github.com
```

then publish:
```bash
npm publish --registry=https://npm.pkg.github.com
```

## Roadmap
### 🚧 in development
- [x] hospedagem: vercel;
- [x] visualização de clusters de pontos;
- [x] visualização de linhas (rotas, conexões) no mapa;
- [x] visualização de imagens georeferenciadas;
- [x] visualização de polígonos (áreas, regiões) no mapa;
- [x] upload de dados (txt, CSV, GeoJSON, Shapefiles, KML/KMZ): em colunas de latitude/longitude;
- [x] cálculo de distâncias;
- [x] desenho derrota;

### **Next Releases**

#### **Release v2.1.0 - Add Content**

- [ ] lighthouses, tide stations, and ETA calculations
- [ ] ship Tracking - real-time vessel monitoring and trackin
- [ ] controle de opacidade da layer;
- [ ] integração com APIs de dados externos: AIS

#### **Release v2.2.0 - Add Features**

- [ ] alertas de colisão baseados em rotas;
- [ ] otimização de rotas considerando correntes e clima;
- [ ] pontos coloridos por valor;
- [ ] popups com detalhes ao clicar;
- [ ] correntes marítimas com vetores animados;
- [ ] heatmaps (densidade de dados: população, temperatura, profundidade);
- [ ] painel lateral com estatísticas;
- [ ] gráficos sincronizados com o mapa (ao selecionar área, atualiza gráficos)
- [ ] pesquisa rápida
- [ ] filtros dinâmicos em tempo real;
- [ ] filtros por data, categoria, região;
- [ ] consultas espaciais ("dentro de", "próximo a");
- [ ] slider range da timeline para visualização de dados históricos
- [ ] exportação de visualização de imagens, relatórios [pdf, txt];

### 💡 in concept
- [ ] workspaces salvos na nuvem, privado ou compartilhado
- [ ] compartilhamento de visualizações via link
- [ ] anotações colaborativas no mapa
- [ ] salvar/recuperar workspace;
- [ ] compartilhamento de dashboards
- [ ] salvamento de configurações

## Developer setup
```bash
npm install tslib leaflet
npm install --save-dev @types/leaflet
npm install --save-dev rollup @rollup/plugin-url @rollup/plugin-typescript rollup-plugin-postcss 
```

## Git setup for developer
```bash
git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/InstitutoHidrografico/leaflet-toolkit.git
git push -u origin main
```

## Contributing
We welcome contributions! Please see our Contributing Guidelines for details on how to submit pull requests, report issues, and suggest enhancements.
1. **Fork** repository;
2. **Clone** the fork: `git clone https://github.com/hidrografico/leaflet-toolkit.git`;
2. Create a **branch**: `git checkout -b feature/AmazingFeature`;
3. **Commit** yours changes: `git commit -m 'Add some AmazingFeature'`;
4. **Push** to branch (git push origin feature/AmazingFeature);
5. Open a **Pull Request**.

Questions? Open an [issue](https://github.com/institutohidrografico/leaflet-toolkit/issues)!

## Developers
> [Gadelha TI](https://github.com/gadelhati)

## Licence
> [Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)
```
								 Apache License
						   Version 2.0, January 2004
						http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

	  "License" shall mean the terms and conditions for use, reproduction,
	  and distribution as defined by Sections 1 through 9 of this document.

	  "Licensor" shall mean the copyright owner or entity authorized by
	  the copyright owner that is granting the License.

	  "Legal Entity" shall mean the union of the acting entity and all
	  other entities that control, are controlled by, or are under common
	  control with that entity. For the purposes of this definition,
	  "control" means (i) the power, direct or indirect, to cause the
	  direction or management of such entity, whether by contract or
	  otherwise, or (ii) ownership of fifty percent (50%) or more of the
	  outstanding shares, or (iii) beneficial ownership of such entity.

	  "You" (or "Your") shall mean an individual or Legal Entity
	  exercising permissions granted by this License.

	  "Source" form shall mean the preferred form for making modifications,
	  including but not limited to software source code, documentation
	  source, and configuration files.

	  "Object" form shall mean any form resulting from mechanical
	  transformation or translation of a Source form, including but
	  not limited to compiled object code, generated documentation,
	  and conversions to other media types.

	  "Work" shall mean the work of authorship, whether in Source or
	  Object form, made available under the License, as indicated by a
	  copyright notice that is included in or attached to the work
	  (an example is provided in the Appendix below).

	  "Derivative Works" shall mean any work, whether in Source or Object
	  form, that is based on (or derived from) the Work and for which the
	  editorial revisions, annotations, elaborations, or other modifications
	  represent, as a whole, an original work of authorship. For the purposes
	  of this License, Derivative Works shall not include works that remain
	  separable from, or merely link (or bind by name) to the interfaces of,
	  the Work and Derivative Works thereof.

	  "Contribution" shall mean any work of authorship, including
	  the original version of the Work and any modifications or additions
	  to that Work or Derivative Works thereof, that is intentionally
	  submitted to Licensor for inclusion in the Work by the copyright owner
	  or by an individual or Legal Entity authorized to submit on behalf of
	  the copyright owner. For the purposes of this definition, "submitted"
	  means any form of electronic, verbal, or written communication sent
	  to the Licensor or its representatives, including but not limited to
	  communication on electronic mailing lists, source code control systems,
	  and issue tracking systems that are managed by, or on behalf of, the
	  Licensor for the purpose of discussing and improving the Work, but
	  excluding communication that is conspicuously marked or otherwise
	  designated in writing by the copyright owner as "Not a Contribution."

	  "Contributor" shall mean Licensor and any individual or Legal Entity
	  on behalf of whom a Contribution has been received by Licensor and
	  subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
	  this License, each Contributor hereby grants to You a perpetual,
	  worldwide, non-exclusive, no-charge, royalty-free, irrevocable
	  copyright license to reproduce, prepare Derivative Works of,
	  publicly display, publicly perform, sublicense, and distribute the
	  Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
	  this License, each Contributor hereby grants to You a perpetual,
	  worldwide, non-exclusive, no-charge, royalty-free, irrevocable
	  (except as stated in this section) patent license to make, have made,
	  use, offer to sell, sell, import, and otherwise transfer the Work,
	  where such license applies only to those patent claims licensable
	  by such Contributor that are necessarily infringed by their
	  Contribution(s) alone or by combination of their Contribution(s)
	  with the Work to which such Contribution(s) was submitted. If You
	  institute patent litigation against any entity (including a
	  cross-claim or counterclaim in a lawsuit) alleging that the Work
	  or a Contribution incorporated within the Work constitutes direct
	  or contributory patent infringement, then any patent licenses
	  granted to You under this License for that Work shall terminate
	  as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
	  Work or Derivative Works thereof in any medium, with or without
	  modifications, and in Source or Object form, provided that You
	  meet the following conditions:

	  (a) You must give any other recipients of the Work or
		  Derivative Works a copy of this License; and

	  (b) You must cause any modified files to carry prominent notices
		  stating that You changed the files; and

	  (c) You must retain, in the Source form of any Derivative Works
		  that You distribute, all copyright, patent, trademark, and
		  attribution notices from the Source form of the Work,
		  excluding those notices that do not pertain to any part of
		  the Derivative Works; and

	  (d) If the Work includes a "NOTICE" text file as part of its
		  distribution, then any Derivative Works that You distribute must
		  include a readable copy of the attribution notices contained
		  within such NOTICE file, excluding those notices that do not
		  pertain to any part of the Derivative Works, in at least one
		  of the following places: within a NOTICE text file distributed
		  as part of the Derivative Works; within the Source form or
		  documentation, if provided along with the Derivative Works; or,
		  within a display generated by the Derivative Works, if and
		  wherever such third-party notices normally appear. The contents
		  of the NOTICE file are for informational purposes only and
		  do not modify the License. You may add Your own attribution
		  notices within Derivative Works that You distribute, alongside
		  or as an addendum to the NOTICE text from the Work, provided
		  that such additional attribution notices cannot be construed
		  as modifying the License.

	  You may add Your own copyright statement to Your modifications and
	  may provide additional or different license terms and conditions
	  for use, reproduction, or distribution of Your modifications, or
	  for any such Derivative Works as a whole, provided Your use,
	  reproduction, and distribution of the Work otherwise complies with
	  the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
	  any Contribution intentionally submitted for inclusion in the Work
	  by You to the Licensor shall be under the terms and conditions of
	  this License, without any additional terms or conditions.
	  Notwithstanding the above, nothing herein shall supersede or modify
	  the terms of any separate license agreement you may have executed
	  with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
	  names, trademarks, service marks, or product names of the Licensor,
	  except as required for reasonable and customary use in describing the
	  origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
	  agreed to in writing, Licensor provides the Work (and each
	  Contributor provides its Contributions) on an "AS IS" BASIS,
	  WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
	  implied, including, without limitation, any warranties or conditions
	  of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
	  PARTICULAR PURPOSE. You are solely responsible for determining the
	  appropriateness of using or redistributing the Work and assume any
	  risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
	  whether in tort (including negligence), contract, or otherwise,
	  unless required by applicable law (such as deliberate and grossly
	  negligent acts) or agreed to in writing, shall any Contributor be
	  liable to You for damages, including any direct, indirect, special,
	  incidental, or consequential damages of any character arising as a
	  result of this License or out of the use or inability to use the
	  Work (including but not limited to damages for loss of goodwill,
	  work stoppage, computer failure or malfunction, or any and all
	  other commercial damages or losses), even if such Contributor
	  has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
	  the Work or Derivative Works thereof, You may choose to offer,
	  and charge a fee for, acceptance of support, warranty, indemnity,
	  or other liability obligations and/or rights consistent with this
	  License. However, in accepting such obligations, You may act only
	  on Your own behalf and on Your sole responsibility, not on behalf
	  of any other Contributor, and only if You agree to indemnify,
	  defend, and hold each Contributor harmless for any liability
	  incurred by, or claims asserted against, such Contributor by reason
	  of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

	  To apply the Apache License to your work, attach the following
	  boilerplate notice, with the fields enclosed by brackets "[]"
	  replaced with your own identifying information. (Don't include
	  the brackets!)  The text should be enclosed in the appropriate
	  comment syntax for the file format. We also recommend that a
	  file or class name and description of purpose be included on the
	  same "printed page" as the copyright notice for easier
	  identification within third-party archives.

   Copyright [2025] [Instituto Hidrográfico]

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

	   http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

<div align="center">

Leaflet Toolkit - Navigating the future of geospatial data visualization 🌍

**⭐ Did you like the project? Leave a star! ⭐**

[![GitHub stars](https://img.shields.io/github/stars/gadelhati/maps-back?style=social)](https://github.com/gadelhati/maps-back)
[![GitHub forks](https://img.shields.io/github/forks/gadelhati/maps-back?style=social)](https://github.com/gadelhati/maps-back/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/gadelhati/maps-back?style=social)](https://github.com/gadelhati/maps-back)

**Made by [Gadelha TI](https://github.com/gadelhati)**

</div>