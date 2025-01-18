# Third-Party Licenses

This project uses third-party Docker images. The respective licenses are listed below:

--------------------------------------------------------------------------------

1. Telegraf & InfluxDB

- Images: `telegraf:latest`, `influxdb:2`
- License: MIT License
- Source Links:
  - Telegraf: https://hub.docker.com/_/telegraf
  - InfluxDB: https://hub.docker.com/_/influxdb

MIT License Terms:
--------------------------------------------------------------------------------
Copyright (c) InfluxData

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Important Notes:
- Ensure that any modifications to InfluxDB or Telegraf are clearly documented.
- Provide appropriate attribution if distributing or referencing these images.
- Include the full MIT License text wherever required.

--------------------------------------------------------------------------------

2. Grafana

- Image: `grafana/grafana-oss`
- License: GNU Affero General Public License v3 (AGPLv3)
- Source: https://grafana.com/licensing/

AGPLv3 License Compliance:
--------------------------------------------------------------------------------
To respect the licensing of the open source Grafana Docker image, you should be 
aware of the following key points:

1. **License Terms**:
   - Grafana's open source edition is licensed under the GNU Affero General 
     Public License (AGPL) v3. This change was made in 2021 when Grafana Labs 
     relicensed their core open source projects from Apache 2.0 to AGPLv3.
   - Official Docker Image for Grafana Open Source: `grafana/grafana-oss`

2. **Your Obligations When Using AGPLv3**:
   - Provide a copy of the AGPLv3 license to recipients of your work.
   - If you modify Grafana and make it available to others (either as a 
     distribution or over a network), you must share the source code of your 
     modifications.

3. **Your Rights**:
   - You are free to use, modify, and distribute Grafana OSS as long as you 
     comply with the AGPLv3 license terms.

4. **Attribution & Documentation**:
   - When creating your guide, include appropriate attribution and license 
     information.
   - Mention that Grafana OSS is licensed under AGPLv3 and provide a link to 
     the official license: https://grafana.com/licensing/.

5. **Third-Party Components**:
   - Be aware that some components of Grafana may include third-party open 
     source software with different licenses. These must be respected 
     according to Grafana Labs’ License Agreement.

Important Compliance Links:
- AGPLv3 License Details: https://www.gnu.org/licenses/agpl-3.0.html
- Grafana Licensing Information: https://grafana.com/licensing/
