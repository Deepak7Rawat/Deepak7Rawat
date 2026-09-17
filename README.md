from pathlib import Path

out = Path("/mnt/data")

dark = '''<svg xmlns="http://www.w3.org/2000/svg" width="1180" height="610" viewBox="0 0 1180 610" role="img" aria-label="Animated developer profile banner">
<defs>
<linearGradient id="a" x1="0%" y1="0%" x2="100%" y2="0%">
<stop offset="0%" stop-color="#7C3AED"><animate attributeName="stop-color" values="#7C3AED;#22D3EE;#10B981;#7C3AED" dur="9s" repeatCount="indefinite"/></stop>
<stop offset="50%" stop-color="#22D3EE"><animate attributeName="stop-color" values="#22D3EE;#10B981;#7C3AED;#22D3EE" dur="9s" repeatCount="indefinite"/></stop>
<stop offset="100%" stop-color="#10B981"><animate attributeName="stop-color" values="#10B981;#7C3AED;#22D3EE;#10B981" dur="9s" repeatCount="indefinite"/></stop></linearGradient>
<radialGradient id="b"><stop stop-color="#2563EB" stop-opacity=".20"/><stop offset="1" stop-color="#2563EB" stop-opacity="0"/></radialGradient>
<radialGradient id="c"><stop stop-color="#7C3AED" stop-opacity=".18"/><stop offset="1" stop-color="#7C3AED" stop-opacity="0"/></radialGradient>
<filter id="g"><feGaussianBlur stdDeviation="5" result="x"/><feMerge><feMergeNode in="x"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
<filter id="blur"><feGaussianBlur stdDeviation="25"/></filter>
<clipPath id="r"><rect width="1180" height="610" rx="28"/></clipPath>
</defs>
<g clip-path="url(#r)">
<rect width="1180" height="610" fill="#030712"/>
<circle cx="140" cy="80" r="300" fill="url(#b)" filter="url(#blur)"><animateTransform attributeName="transform" type="translate" values="0 0;30 15;0 0" dur="12s" repeatCount="indefinite"/></circle>
<circle cx="1050" cy="500" r="300" fill="url(#c)" filter="url(#blur)"><animateTransform attributeName="transform" type="translate" values="0 0;-30 -20;0 0" dur="15s" repeatCount="indefinite"/></circle>

<g fill="#fff" opacity=".14">
<circle cx="60" cy="90" r="1"><animate attributeName="opacity" values=".03;.4;.03" dur="3s" repeatCount="indefinite"/></circle>
<circle cx="350" cy="45" r="1"><animate attributeName="opacity" values=".4;.03;.4" dur="4s" repeatCount="indefinite"/></circle>
<circle cx="650" cy="560" r="1"><animate attributeName="opacity" values=".03;.4;.03" dur="3.5s" repeatCount="indefinite"/></circle>
<circle cx="1110" cy="95" r="1"><animate attributeName="opacity" values=".35;.03;.35" dur="5s" repeatCount="indefinite"/></circle>
</g>

<rect x="28" y="28" width="410" height="554" rx="24" fill="#0F172A" fill-opacity=".72" stroke="#fff" stroke-opacity=".08"/>
<rect x="458" y="28" width="694" height="554" rx="24" fill="#0F172A" fill-opacity=".76" stroke="#fff" stroke-opacity=".08"/>

<path d="M458 80H1152" stroke="url(#a)" stroke-opacity=".65" stroke-dasharray="120 574">
<animate attributeName="stroke-dashoffset" values="694;0;-694" dur="7s" repeatCount="indefinite"/></path>
<path d="M30 45H436" stroke="url(#a)" stroke-opacity=".55" stroke-dasharray="90 316">
<animate attributeName="stroke-dashoffset" values="406;0;-406" dur="8s" repeatCount="indefinite"/></path>

<!-- animated ASCII portrait -->
<g font-family="ui-monospace,SFMono-Regular,Menlo,Consolas,monospace" font-size="15" font-weight="700" fill="url(#a)" filter="url(#g)">
<animateTransform attributeName="transform" type="translate" values="0 0;0 -4;0 0" dur="5s" repeatCount="indefinite"/>
<text x="55" y="105" opacity="0">          .-''''-.<animate attributeName="opacity" begin=".2s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="124" opacity="0">       .-'  .--.  '-.<animate attributeName="opacity" begin=".45s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="143" opacity="0">     .'   /    \    '.<animate attributeName="opacity" begin=".7s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="162" opacity="0">    /    |  ()  |     \<animate attributeName="opacity" begin=".95s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="181" opacity="0">   ;      \____/       ;<animate attributeName="opacity" begin="1.2s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="200" opacity="0">   |   .-========-.    |<animate attributeName="opacity" begin="1.45s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="219" opacity="0">   ;  /  .-''''-.  \   ;<animate attributeName="opacity" begin="1.7s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="238" opacity="0">    \ |  |  /\  |  |  /<animate attributeName="opacity" begin="1.95s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="257" opacity="0">     '._\  \/  /_./'<animate attributeName="opacity" begin="2.2s" dur=".4s" values="0;1" fill="freeze"/></text>
<text x="55" y="276" opacity="0">        '------'<animate attributeName="opacity" begin="2.45s" dur=".4s" values="0;1" fill="freeze"/></text>
</g>

<text x="55" y="335" fill="#94A3B8" font-family="ui-monospace,monospace" font-size="12" letter-spacing="2">DEVELOPER / CREATOR</text>
<text x="55" y="365" fill="#F8FAFC" font-family="ui-sans-serif,sans-serif" font-size="24" font-weight="700">Deepak Rawat</text>
<text x="55" y="393" fill="#94A3B8" font-family="ui-monospace,monospace" font-size="13">build • learn • ship</text>
<rect x="55" y="430" width="320" height="1" fill="#fff" opacity=".08"/>
<text x="55" y="465" fill="#94A3B8" font-family="ui-monospace,monospace" font-size="12">SYSTEM STATUS</text>
<circle cx="57" cy="488" r="4" fill="#10B981" filter="url(#g)"><animate attributeName="r" values="3;5;3" dur="1.6s" repeatCount="indefinite"/></circle>
<text x="70" y="492" fill="#CBD5E1" font-family="ui-monospace,monospace" font-size="12">online · coding</text>

<!-- terminal -->
<circle cx="487" cy="56" r="5" fill="#ef4444"/><circle cx="505" cy="56" r="5" fill="#eab308"/><circle cx="523" cy="56" r="5" fill="#22c55e"/>
<text x="550" y="61" fill="#64748B" font-family="ui-monospace,monospace" font-size="12">deepak@github ~</text>
<text x="492" y="112" fill="#22D3EE" font-family="ui-monospace,monospace" font-size="15">$ whoami</text>
<text x="492" y="143" fill="#F8FAFC" font-family="ui-sans-serif,sans-serif" font-size="28" font-weight="700">Hi 👋 I'm Deepak Rawat</text>
<text x="492" y="178" fill="#94A3B8" font-family="ui-monospace,monospace" font-size="15">$ role --live</text>

<g font-family="ui-monospace,monospace" font-size="18" fill="url(#a)" font-weight="700">
<text x="492" y="211">Frontend Engineer<tspan fill="#F8FAFC">_</tspan><animate attributeName="opacity" values="1;1;0;0" keyTimes="0;.24;.26;1" dur="12s" repeatCount="indefinite"/></text>
<text x="492" y="211" opacity="0">Full Stack Developer<tspan fill="#F8FAFC">_</tspan><animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;.24;.26;.49;.51" dur="12s" repeatCount="indefinite"/></text>
<text x="492" y="211" opacity="0">Open Source Contributor<tspan fill="#F8FAFC">_</tspan><animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;.49;.51;.74;.76" dur="12s" repeatCount="indefinite"/></text>
<text x="492" y="211" opacity="0">AI Enthusiast<tspan fill="#F8FAFC">_</tspan><animate attributeName="opacity" values="0;0;1;1;0" keyTimes="0;.74;.76;1;1" dur="12s" repeatCount="indefinite"/></text>
</g>

<g font-family="ui-monospace,monospace" font-size="13">
<g opacity="0"><text x="492" y="254" fill="#22D3EE">LOCATION</text><text x="650" y="254" fill="#E2E8F0">India</text><animate attributeName="opacity" begin=".4s" dur=".5s" values="0;1" fill="freeze"/></g>
<g opacity="0"><text x="492" y="282" fill="#22D3EE">EDUCATION</text><text x="650" y="282" fill="#E2E8F0">BCA · 3rd Semester</text><animate attributeName="opacity" begin=".8s" dur=".5s" values="0;1" fill="freeze"/></g>
<g opacity="0"><text x="492" y="310" fill="#22D3EE">FOCUS</text><text x="650" y="310" fill="#E2E8F0">Software · Web · Data</text><animate attributeName="opacity" begin="1.2s" dur=".5s" values="0;1" fill="freeze"/></g>
<g opacity="0"><text x="492" y="338" fill="#22D3EE">PORTFOLIO</text><text x="650" y="338" fill="#E2E8F0">github.com/Deepak7Rawat</text><animate attributeName="opacity" begin="1.6s" dur=".5s" values="0;1" fill="freeze"/></g>
<g opacity="0"><text x="492" y="366" fill="#22D3EE">EMAIL</text><text x="650" y="366" fill="#E2E8F0">open to collaboration</text><animate attributeName="opacity" begin="2s" dur=".5s" values="0;1" fill="freeze"/></g>
</g>

<text x="492" y="414" fill="#94A3B8" font-family="ui-monospace,monospace" font-size="12" letter-spacing="2">STACK</text>
<g font-family="ui-sans-serif,sans-serif" font-size="12" font-weight="600" fill="#0B1220" stroke="url(#a)" stroke-opacity=".7">
<rect x="492" y="432" width="70" height="30" rx="15"/><rect x="570" y="432" width="76" height="30" rx="15"/><rect x="654" y="432" width="70" height="30" rx="15"/><rect x="732" y="432" width="92" height="30" rx="15"/><rect x="832" y="432" width="82" height="30" rx="15"/><rect x="922" y="432" width="70" height="30" rx="15"/><rect x="1000" y="432" width="72" height="30" rx="15"/>
<animateTransform attributeName="transform" type="scale" values="1;1.01;1" dur="3s" repeatCount="indefinite"/>
</g>
<g fill="#CBD5E1" font-family="ui-sans-serif,sans-serif" font-size="12" font-weight="600">
<text x="527" y="451" text-anchor="middle">React</text><text x="608" y="451" text-anchor="middle">Next.js</text><text x="689" y="451" text-anchor="middle">Node.js</text><text x="778" y="451" text-anchor="middle">TypeScript</text><text x="873" y="451" text-anchor="middle">Python</text><text x="957" y="451" text-anchor="middle">Docker</text><text x="1036" y="451" text-anchor="middle">Git</text>
</g>
<g fill="#CBD5E1" font-family="ui-sans-serif,sans-serif" font-size="12" font-weight="600">
<text x="530" y="491" text-anchor="middle">Tailwind</text><text x="620" y="491" text-anchor="middle">Postgres</text><text x="703" y="491" text-anchor="middle">AWS</text><text x="775" y="491" text-anchor="middle">Figma</text><text x="853" y="491" text-anchor="middle">SQL</text>
</g>
<g fill="none" stroke="url(#a)" stroke-opacity=".5"><rect x="492" y="472" width="76" height="30" rx="15"/><rect x="576" y="472" width="88" height="30" rx="15"/><rect x="672" y="472" width="62" height="30" rx="15"/><rect x="742" y="472" width="66" height="30" rx="15"/><rect x="816" y="472" width="74" height="30" rx="15"/></g>

<text x="492" y="542" fill="#64748B" font-family="ui-monospace,monospace" font-size="12">$ connect --with-me</text>
<g fill="#E2E8F0" font-family="ui-sans-serif,sans-serif" font-size="12"><text x="650" y="542">GH</text><text x="700" y="542">in</text><text x="748" y="542">X</text><text x="792" y="542">↗</text></g>

<!-- scanline sweep -->
<rect x="-10" y="0" width="6" height="610" fill="#fff" opacity=".035"><animate attributeName="x" values="-10;1190" dur="8s" repeatCount="indefinite"/></rect>
</g>
<rect x="1" y="1" width="1178" height="608" rx="28" fill="none" stroke="url(#a)" stroke-opacity=".35"><animate attributeName="stroke-opacity" values=".2;.7;.2" dur="5s" repeatCount="indefinite"/></rect>
</svg>'''

light = dark
repls = [
('#030712','#FFFFFF'),('#0F172A','#F8FAFC'),('#F8FAFC','#0F172A'),('#94A3B8','#475569'),
('#CBD5E1','#334155'),('#E2E8F0','#0F172A'),('#0B1220','#FFFFFF'),
('#7C3AED','#2563EB'),('#22D3EE','#06B6D4'),
('stop-opacity=".20"','stop-opacity=".10"'),('stop-opacity=".18"','stop-opacity=".08'),
('stroke="#fff" stroke-opacity=".08"','stroke="#0F172A" stroke-opacity=".08'),
('fill="#fff" opacity=".14"','fill="#0F172A" opacity=".10'),
('fill="#fff" opacity=".035"','fill="#0F172A" opacity=".035')
]
for a,b in repls:
    light = light.replace(a,b)

(out/"dark.svg").write_text(dark, encoding="utf-8")
(out/"light.svg").write_text(light, encoding="utf-8")
print("Created:")
print(out/"dark.svg")
print(out/"light.svg")
