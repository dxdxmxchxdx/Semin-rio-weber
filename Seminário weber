<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Max Weber — Uma experiência interativa</title>
<style>
:root{
  --bg:#080b10;--panel:#10161e;--line:#26313d;--text:#f4f7fa;
  --muted:#aeb8c4;--accent:#00c8e8;--accent2:#7cecff;
}
*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{font-family:Inter,Arial,Helvetica,sans-serif;background:var(--bg);color:var(--text);line-height:1.6}
nav{position:fixed;top:0;left:0;width:100%;z-index:20;display:flex;justify-content:space-between;align-items:center;padding:16px 7%;background:rgba(8,11,16,.86);backdrop-filter:blur(14px);border-bottom:1px solid rgba(255,255,255,.07)}
.logo{font-weight:900;letter-spacing:3px}
nav a{color:#fff;text-decoration:none;font-size:12px;margin-left:18px}
nav a:hover{color:var(--accent)}
section{min-height:100vh;padding:110px 8%;display:flex;flex-direction:column;justify-content:center}
.hero{position:relative;overflow:hidden;text-align:center;background:
radial-gradient(circle at 78% 18%,rgba(0,200,232,.16),transparent 28%),
radial-gradient(circle at 18% 80%,rgba(0,200,232,.08),transparent 30%)}
.hero h1{font-size:clamp(58px,12vw,150px);letter-spacing:-6px;line-height:.9}
.eyebrow{text-transform:uppercase;letter-spacing:4px;color:var(--accent);font-size:12px;font-weight:800;margin-bottom:16px}
.subtitle,.intro{max-width:760px;color:var(--muted);font-size:18px}
.hero .subtitle{margin:28px auto}
.cta{display:inline-block;margin-top:30px;padding:14px 23px;border-radius:999px;background:var(--accent);color:#061014;text-decoration:none;font-weight:900;border:0;transition:.25s}
.cta:hover{transform:translateY(-3px);box-shadow:0 12px 30px rgba(0,200,232,.22)}
.section-title{font-size:clamp(42px,6vw,78px);line-height:1;margin-bottom:18px;letter-spacing:-2px}
.timeline-wrap{margin-top:55px}
.timeline{display:flex;overflow-x:auto;padding:30px 5px 45px;scrollbar-color:var(--accent) var(--panel)}
.event{min-width:245px;padding:24px 24px 10px;border-top:2px solid var(--accent);position:relative}
.event:before{content:"";position:absolute;left:20px;top:-9px;width:14px;height:14px;border-radius:50%;background:var(--accent);box-shadow:0 0 0 5px rgba(0,200,232,.10)}
.year{font-size:32px;font-weight:900;color:var(--accent)}
.event h3{font-size:20px;margin:8px 0}
.event p{font-size:14px;color:var(--muted)}
.history-grid{display:grid;grid-template-columns:1.1fr .9fr;gap:35px;align-items:center;margin-top:35px}
.image-card{background:var(--panel);border:1px solid var(--line);border-radius:24px;padding:12px;overflow:hidden}
.image-card img{width:100%;display:block;border-radius:16px;max-height:520px;object-fit:cover}
.caption{font-size:12px;color:#8793a0;padding:12px 5px 3px}
.bio{display:grid;grid-template-columns:.9fr 1.1fr;gap:50px;align-items:center}
.portrait{border-radius:24px;overflow:hidden;border:1px solid var(--line);background:#111}
.portrait img{width:100%;display:block;filter:grayscale(100%);transition:.5s}
.portrait:hover img{filter:grayscale(20%);transform:scale(1.02)}
.year-big{font-size:clamp(80px,13vw,160px);font-weight:900;color:transparent;-webkit-text-stroke:1px var(--accent);line-height:.85;margin-bottom:18px}
.info-list{display:grid;gap:14px;margin-top:24px}
.info{background:var(--panel);border-left:3px solid var(--accent);padding:18px 20px;border-radius:0 14px 14px 0}
.info strong{display:block;color:var(--accent);font-size:12px;letter-spacing:1.5px;margin-bottom:4px}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px;margin-top:45px}
.card{background:var(--panel);border:1px solid var(--line);border-radius:20px;padding:26px;transition:.25s}
.card:hover{transform:translateY(-5px);border-color:var(--accent)}
.card h3{font-size:24px;margin:10px 0}
.card p{color:var(--muted)}
.card .num{color:var(--accent);font-weight:900;font-size:12px}
.family{display:grid;grid-template-columns:repeat(2,1fr);gap:18px;margin-top:40px}
.family .card{min-height:210px}
