<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>Generador de Documentos DARH</title>
<style>
:root{
  --az:#003F8A;--az2:#002660;--az3:#1565C0;--dor:#C9A84C;
  --cel:#EEF4FB;--celb:#C5D9F0;--gbg:#DDE1E8;--gp:#F5F6F8;
  --gb:#D0D6E0;--tx:#1A2535;--su:#5A6478;--vd:#1A7A4A;
  --hn:#FFECC8;--hf:#C8EFCF;--hl:#C4EBF2;--hd:#FFD6DB;--he:#DDD0FF;
}
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
img{border:none!important;outline:none!important;box-shadow:none!important;}
html,body{height:100%;overflow:auto;}
body{font-family:Calibri,'Barlow',sans-serif;background:var(--gbg);color:var(--tx);font-size:15px;display:flex;flex-direction:column;}
.hdr{background:linear-gradient(92deg,var(--az2) 0%,var(--az) 55%,#1457B3 100%);border-bottom:3px solid var(--dor);flex-shrink:0;box-shadow:0 3px 14px rgba(0,0,0,.28);}
.hdr-i{display:flex;align-items:center;gap:14px;padding:9px 20px;}
.hdr-logo{height:50px;width:auto;border-radius:3px;flex-shrink:0;}
.hdr-sep{width:1px;height:38px;background:rgba(255,255,255,.2);flex-shrink:0;}
.hdr-t h1{font-family:'Barlow Condensed',sans-serif;font-size:19px;font-weight:700;color:#fff;letter-spacing:.05em;text-transform:uppercase;line-height:1.15;}
.hdr-t p{font-size:11px;color:rgba(255,255,255,.6);letter-spacing:.06em;text-transform:uppercase;margin-top:2px;}
.hdr-b{margin-left:auto;flex-shrink:0;background:rgba(255,255,255,.1);border:1px solid rgba(255,255,255,.2);border-radius:20px;padding:5px 14px;font-size:10px;color:rgba(255,255,255,.75);letter-spacing:.07em;text-transform:uppercase;}
.ws{flex:1;display:flex;overflow:hidden;min-height:0;}
