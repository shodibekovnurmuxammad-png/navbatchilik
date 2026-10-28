<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Uyga qarab olg’a</title>
<style>
:root{--bg:#f6f4ee;--card:#fff;--ink:#1d1d1b;--mute:#6b6a64;--acc:#1d7a5f;--accink:#fff;--bad:#c0392b;--line:#ddd9cc;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#17181a;--card:#222426;--ink:#f1efe8;--mute:#9b9a92;--acc:#3fb58f;--accink:#08130f;--bad:#ef6f60;--line:#34363a}}
:root[data-theme="dark"]{--bg:#17181a;--card:#222426;--ink:#f1efe8;--mute:#9b9a92;--acc:#3fb58f;--accink:#08130f;--bad:#ef6f60;--line:#34363a}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;min-height:100vh}
main{max-width:640px;margin:0 auto;padding:20px 16px 40px}
h1{font-size:28px;margin:8px 0 4px}
p.sub{color:var(--mute);margin:0 0 20px}
.card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:18px;margin-bottom:16px}
label{display:block;font-weight:600;margin-bottom:6px}
input[type=number]{width:100%;font-size:22px;padding:12px;border-radius:12px;border:1px solid var(--line);background:var(--bg);color:var(--ink)}
.row{display:flex;gap:12px}.row>div{flex:1}
button{font:inherit;font-weight:700;border:0;border-radius:12px;padding:14px 18px;background:var(--acc);color:var(--accink);cursor:pointer}
button.ghost{background:transparent;color:var(--ink);border:1px solid var(--line)}
button.full{width:100%;margin-top:14px}
.hint{color:var(--mute);font-size:14px;margin-top:8px}
.grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(110px,1fr));gap:10px}
.num{font-size:26px;font-weight:800;border-radius:14px;background:var(--card);color:var(--ink);border:2px solid var(--line);padding:12px 6px;line-height:1.2}
.num small{display:block;font-size:12px;font-weight:600;color:var(--mute);margin-top:4px}
.num.lose small{color:#fff}
.num.taken{opacity:.3;pointer-events:none;text-decoration:line-through
