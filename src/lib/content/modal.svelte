<script>
    toggleInterruption = (elName) => {
        let interruption = document.querySelector(elName);
        const html = document.querySelector('html');

        interruption.hasAttribute('open')
            ? interruption.removeAttribute("open")
            : (interruption.removeAttribute("open"),
                interruption.setAttribute("open", true))
    }

</script>
<auro-dialog id="priority">
    <span slot="header">Flight Loads</span>
    <span slot="content">
        <table class="auro_table">
            <thead>
                <tr>
                    <th>Class</th>
                    <th>Cnfg</th>
                    <th>Auth</th>
                    <th>Cnfg Open</th>
                    <th>Auth Open</th>
                    <th>PST</th>
                    <th>Listed</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>J</td>
                    <td>16</td>
                    <td>16</td>
                    <td class="">0</td>
                    <td class="">0</td>
                    <td class="" rowspan="2">0</td>
                    <td rowspan="2">4</td>
                </tr>
                <tr>
                    <td>Y</td>
                    <td>162</td>
                    <td>162</td>
                    <td class="">25</td>
                    <td class="">25</td>
                </tr>
            </tbody>
        </table>
        <auro-header display="400">Legend</auro-header>
        <table class="auro_table auro_table-border">
            <thead>
                <tr>
                    <th scope="row"><span>Code</span></th>
                    <th><span>Description</span></th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <th scope="row"><span>D1</span></th>
                    <th><span>OAL Employee: Business</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>D4</span></th>
                    <th><span>AS/QX Employee: Business</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>D8Y</span></th>
                    <th><span>AS EMP: Registered Commuter</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>D9</span></th>
                    <th><span>AS Dir &amp; dep. CPN w/dir/sp/DP/PT. Par w/dir/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>D9A</span></th>
                    <th><span>QX Dir &amp; dep. CPN w/dir/sp/DP/PT. Par w/dir/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E1Y</span></th>
                    <th><span>AS EMP &amp; deps. CPN w/emp/sp/DP/PT. Par w/emp/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E2Y</span></th>
                    <th><span>AS Ret/VSI &amp; dep. CPN w/ret/sp/DP. Par w/ret/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E3Y</span></th>
                    <th><span>AS Parent traveling alone</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E5YA</span></th>
                    <th><span>QX EMP &amp; deps. CPN w/emp/sp/DP/PT. Par w/emp/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E5YB</span></th>
                    <th><span>QX Ret/VSI &amp; dep. CPN w/ret/sp/DP. Par w/ret/dep</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E5YC</span></th>
                    <th><span>QX Parent traveling alone</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>E6Y</span></th>
                    <th><span>AS/QX Guest Pass</span></th>
                </tr>
                <tr>
                    <th scope="row"><span>Other</span></th>
                    <th><span>Includes all other lower non-revenue priority codes.</span></th>
                </tr>
            </tbody>
        </table>
    </span>
    <span slot="footer">

    </span>
</auro-dialog>
