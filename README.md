  # FPDV

<!----- #### Table1: Performance comparison between MotifCAR and baselines on four datasets. ---->
<h4 align = "center">Table1: Performance comparison between MotifCAR and baselines on four datasets.</h4>
  <table align = "center" style="width:100%;">
    <tr>
        <th align="left" rowspan="2" >Method</th>
        <th colspan="3" >IMDB-BINARY</th>
        <th colspan="3">IMDB-MULTI</th>
        <th colspan="3">REDDIT-BINARY</th>
        <th colspan="3">REDDIT-MULTI-5K</th>
    </tr>
    <tr>
        <td align="center">PRE</td>
        <td align="center">RECALL</td>
        <td align="center">F1</td>
        <td align="center">PRE</td>
        <td align="center">RECALL</td>
        <td align="center">F1</td>
        <td align="center">PRE</td>
        <td align="center">RECALL</td>
        <td align="center">F1</td>
        <td align="center">PRE</td>
        <td align="center">RECALL</td>
        <td align="center">F1</td>
    </tr>
    <tr>
        <td>g-U-Nets</td>
        <td>0.87±0.06</td>
        <td>0.91±0.11</td>
        <td>0.88±0.10</td>
        <td>0.80±0.07</td>
        <td>0.86±0.05</td>
        <td>0.80±0.07</td>
        <td>0.86±0.08</td>
        <td>0.75±0.18</td>
        <td>0.78±0.12</td>
        <td>0.76±0.06</td>
        <td>0.71±0.17</td>
        <td>0.73±0.11</td>
    </tr>
    <tr>
        <td>DiffPool</td>
        <td>066±0.07</td>
        <td>0.69±0.09</td>
        <td>0.81±0.18</td>
        <td>0.65±0.06</td>
        <td>0.70±0.07</td>
        <td>0.83±0.18</td>
        <td>0.71±0.07</td>
        <td>0.63±0.09</td>
        <td>0.64±0.11</td>
        <td>0.71±0.08</td>
        <td>0.61±0.07</td>
        <td>0.71±0.13</td>
    </tr>
    <tr>
        <td>SAGPool</td>
        <td>0.80±0.07</td>
        <td>0.88±0.08</td>
        <td>0.84±0.12</td>
        <td>0.73±0.06</td>
        <td>0.90±0.07</td>
        <td>0.82±0.13</td>
        <td>0.81±0.08</td>
        <td>0.81±0.07</td>
        <td>0.83±0.08</td>
        <td>0.76±0.06</td>
        <td>0.61±0.05</td>
        <td>0.74±0.07</td>
    </tr>
    <tr>
        <td>GMT</td>
        <td>0.83±0.08</td>
        <td>0.88±0.05</td>
        <td>0.88±0.06</td>
        <td>0.82±0.07</td>
        <td>0.84±0.05</td>
        <td>0.83±0.13</td>
        <td>0.83±0.15</td>
        <td>0.83±0.08</td>
        <td>0.83±0.17</td>
        <td>0.78±0.16</td>
        <td>0.80±0.09</td>
        <td>0.67±0.15</td>
    </tr>
    <tr>
        <td nowrap>CFGL-LCR</td>
        <td>0.85±0.13</td>
        <td>0.87±0.12</td>
        <td>0.84±0.12</td>
        <td>083±0.12</td>
        <td>0.83±0.12</td>
        <td>0.76±0.13</td>
        <td>086±0.14</td>
        <td>0.88±0.13</td>
        <td>0.82±0.14</td>
        <td>0.82±0.09</td>
        <td>0.80±0.12</td>
        <td>0.78±0.12</td>
    </tr>
    <tr>
        <td>CFAD</td>
        <td>0.87±0.13</td>
        <td>0.88±0.13</td>
        <td>086±0.13</td>
        <td>0.86±0.13</td>
        <td>0.88±0.13</td>
        <td>0.78±0.13</td>
        <td>0.87±0.13</td>
        <td>0.86±0.13</td>
        <td>0.84±0.12</td>
        <td>0.83±0.08</td>
        <td>0.81±0.11</td>
        <td>0.82±0.11</td>
    </tr>
    <tr>
        <td>CGC</td>
        <td>0.92±0.14</td>
        <td>0.94±0.09</td>
        <td>0.92±0.12</td>
        <td>0.89±0.13</td>
        <td>0.93±0.14</td>
        <td>0.92±0.13</td>
        <td>0.90±0.14</td>
        <td>0.93±0.13</td>
        <td>0.91±0.12</td>
        <td>0.84±0.12</td>
        <td>0.95±0.09</td>
        <td>0.84±0.12</td>
    </tr>
    <tr>
        <td nowrap>CF-HGExp</td>
        <td>0.93±0.12</td>
        <td>0.94±0.12</td>
        <td>0.94±0.11</td>
        <td>0.90±0.13</td>
        <td>0.95±0.12</td>
        <td>0.94±0.14</td>
        <td>0.92±0.12</td>
        <td>0.94±0.13</td>
        <td>0.93±0.11</td>
        <td>0.85±0.13</td>
        <td>0.95±0.13</td>
        <td>0.85±0.13</td>
    </tr>
    <tr>
        <td>OCGTL</td>
        <td>0.88±0.09</td>
        <td>0.89±0.05</td>
        <td>0.87±0.06</td>
        <td>0.82±0.07</td>
        <td>0.84±0.06</td>
        <td>0.80±0.16</td>
        <td>0.89±0.12</td>
        <td>0.89±0.07</td>
        <td>0.88±0.07</td>
        <td>0.86±0.09</td>
        <td>0.84±0.13</td>
        <td>0.82±0.12</td>
    </tr>
    <tr>
        <td>GLocalKD</td>
        <td>0.65±0.11</td>
        <td>0.66±0.07</td>
        <td>0.66±0.07</td>
        <td>0.60±0.06</td>
        <td>0.63±0.13</td>
        <td>0.61±0.13</td>
        <td>0.63±0.12</td>
        <td>0.64±0.08</td>
        <td>0.63±0.06</td>
        <td>0.58±0.09</td>
        <td>0.62±0.13</td>
        <td>0.73±0.12</td>
    </tr>
    <tr>
        <td>iGAD</td>
        <td>0.88±0.07</td>
        <td>0.78±0.06</td>
        <td>0.87±0.08</td>
        <td>0.86±0.06</td>
        <td>0.75±0.07</td>
        <td>0.82±0.06</td>
        <td>0.57±0.23</td>
        <td>0.58±0.31</td>
        <td>0.55±0.23</td>
        <td>0.53±0.22</td>
        <td>0.54±0.28</td>
        <td>0.67±0.23</td>
    </tr>
    <tr>
        <td>GmapAD</td>
        <td>0.92±0.07</td>
        <td>0.94±0.06</td>
        <td>0.94±0.05</td>
        <td>0.90±0.05</td>
        <td>0.95±0.07</td>
        <td>0.93±0.06</td>
        <td>0.91±0.05</td>
        <td>0.96±0.08</td>
        <td>0.95±0.08</td>
        <td>0.87±0.07</td>
        <td>0.95±0.08</td>
        <td>0.86±0.07</td>
    </tr>
    <tr>
        <td>MotiCF</td>
        <td>0.94±0.10</td>
        <td>0.95±0.09</td>
        <td>0.96±0.11</td>
        <td>0.91±0.10</td>
        <td>0.96±0.10</td>
        <td>0.94±0.09</td>
        <td>0.93±0.11</td>
        <td>0.96±0.11</td>
        <td>0.96±0.12</td>
        <td>0.89±0.12</td>
        <td>0.97±0.11</td>
        <td>0.87±0.08</td>
    </tr>
</table>
