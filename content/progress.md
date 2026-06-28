+++
title = "progress"
+++

<style>
h1 { font-size: 1.75rem; }
.pg { margin-bottom: 1rem; }
.pg-row { display: flex; justify-content: space-between; align-items: baseline; gap: 1rem; margin-bottom: 0.25rem; }
.pg-links { display: flex; gap: 0.75rem; flex-shrink: 0; font-size: 0.75rem; }
.pg-links a { color: var(--text-light); }
.bar-track { height: 5px; background: var(--bg-light); border-radius: 3px; overflow: hidden; }
.bar-fill { height: 100%; border-radius: 3px; }
.pg-section { margin-bottom: 1rem; }
/* toolkit grid */
.tk-outer { width: 100vw; margin-left: calc(50% - 50vw); padding: 0 5vw; box-sizing: border-box; }
.tk-grid { display: grid; grid-template-columns: repeat(2, 1fr); column-gap: 4rem; }
.tk-cell h3 { margin-top: 0; }
.tk-cell .pg { margin-bottom: 0.4rem; }
.tk-cell .pg-row { margin-bottom: 0.1rem; }
.tk-cell .pg-label { font-size: 0.8rem; }
.tk-cell .pg-links { font-size: 0.65rem; }
.tk-cell .bar-track { height: 3px; }
@media (max-width: 720px) {
  .tk-outer { width: 100%; margin-left: 0; padding: 0; }
  .tk-grid { grid-template-columns: 1fr; }
}
</style>

<br />

## research

<div class="pg-section">

<div class="pg">
<div class="pg-row"><span class="pg-label">linear networks</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#E05757;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">implicit bias</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#E07A3C;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">edge of stability</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#D4A830;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">wide networks / NTKs</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#5AB547;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">benign overfitting / generalization</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#2DB888;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">empirical results</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#4480D4;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">mode connectivity</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#7060D4;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">statistical query learning, hermite polynomials</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#A84DC2;"></div></div>
</div>

<div class="pg">
<div class="pg-row"><span class="pg-label">logconcave sampling and diffusion</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div>
<div class="bar-track"><div class="bar-fill" style="width:0%;background:#D44A8A;"></div></div>
</div>

</div>

<br />

## toolkit

<div class="tk-outer"><div class="tk-grid">

<div class="tk-cell">
<h3>engineering math</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">calculus</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">differential equations</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">intro to complex numbers</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">fourier series</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">euclidean geometry</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">counting</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#50B8A0;"></div></div></div>
</div>

<div class="tk-cell">
<h3>ml theory / optimization</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">statistical learning theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#3BA8C7;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">optimization theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#3BA8C7;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">optimization on manifolds</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#3BA8C7;"></div></div></div>
</div>

<div class="tk-cell">
<h3>analysis</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">real analysis</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#48B86A;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">measure theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#48B86A;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">functional analysis</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#48B86A;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">fourier analysis</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#48B86A;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">complex analysis</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#48B86A;"></div></div></div>
</div>

<div class="tk-cell">
<h3>probability</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">probability theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D4A030;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">high dimensional probability</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D4A030;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">random matrix theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D4A030;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">asymptotic convex geometry</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D4A030;"></div></div></div>
</div>

<div class="tk-cell">
<h3>algebra</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">group theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D44840;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">linear algebra</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D44840;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">lie groups and lie algebra</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D44840;"></div></div></div>
</div>

<div class="tk-cell">
<h3>differential equations</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">ordinary differential equations</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#5570D4;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">partial differential equations</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#5570D4;"></div></div></div>
</div>

<div class="tk-cell">
<h3>geometry</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">topology</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#8050D0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">differential topology</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#8050D0;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">differential geometry</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#8050D0;"></div></div></div>
</div>

<div class="tk-cell">
<h3>physics</h3>
<div class="pg"><div class="pg-row"><span class="pg-label">classical mechanics</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D04880;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">electromagnetism</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D04880;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">quantum theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D04880;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">special / general relativity</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D04880;"></div></div></div>
<div class="pg"><div class="pg-row"><span class="pg-label">quantum field theory</span><span class="pg-links"><a href="#">[notes]</a><a href="#">[resources]</a></span></div><div class="bar-track"><div class="bar-fill" style="width:0%;background:#D04880;"></div></div></div>
</div>

</div></div>
