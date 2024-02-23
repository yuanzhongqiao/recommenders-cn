<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><h1 tabindex="-1" dir="auto"><a id="user-content-tensorflow-recommenders" class="anchor" aria-hidden="true" tabindex="-1" href="#tensorflow-recommenders"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorFlow 推荐器</font></font></h1>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/tensorflow/recommenders/blob/main/assets/full_logo.png"><img src="/tensorflow/recommenders/raw/main/assets/full_logo.png" alt="TensorFlow 推荐者徽标" style="max-width: 100%;"></a></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="https://github.com/tensorflow/recommenders/actions/workflows/test.yaml/badge.svg"><img src="https://github.com/tensorflow/recommenders/actions/workflows/test.yaml/badge.svg" alt="TensorFlow Recommenders 构建徽章" style="max-width: 100%;"></a>
<a href="https://pypi.python.org/pypi/tensorflow-recommenders/" rel="nofollow"><img src="https://camo.githubusercontent.com/de6361b3c6929323c629532b3f97bf46ce2a2b5868bf39a4ffd04556350191a5/68747470733a2f2f696d672e736869656c64732e696f2f707970692f762f74656e736f72666c6f772d7265636f6d6d656e646572732e737667" alt="PyPI 徽章" data-canonical-src="https://img.shields.io/pypi/v/tensorflow-recommenders.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.tensorflow.org" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">TensorFlow Recommenders 是一个使用TensorFlow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">构建推荐系统模型的库</font><font style="vertical-align: inherit;">。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它有助于构建推荐系统的完整工作流程：数据准备、模型制定、培训、评估和部署。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">它基于 Keras 构建，旨在拥有平缓的学习曲线，同时仍为您提供构建复杂模型的灵活性。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-installation" class="anchor" aria-hidden="true" tabindex="-1" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">确保您已安装 TensorFlow 2.x，并从以下位置安装</font></font><code>pip</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>pip install tensorflow-recommenders</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install tensorflow-recommenders" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-documentation" class="anchor" aria-hidden="true" tabindex="-1" href="#documentation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请查看我们的
</font></font><a href="https://tensorflow.org/recommenders/examples/quickstart" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">教程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和
</font></font><a href="https://www.tensorflow.org/recommenders/api_docs/python/tfrs/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">API 参考</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-quick-start" class="anchor" aria-hidden="true" tabindex="-1" href="#quick-start"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">快速开始</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 Movielens 100K 数据集构建分解模型非常简单（</font></font><a href="https://tensorflow.org/recommenders/examples/quickstart" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Colab</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">）：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">typing</span> <span class="pl-k">import</span> <span class="pl-v">Dict</span>, <span class="pl-v">Text</span>

<span class="pl-k">import</span> <span class="pl-s1">tensorflow</span> <span class="pl-k">as</span> <span class="pl-s1">tf</span>
<span class="pl-k">import</span> <span class="pl-s1">tensorflow_datasets</span> <span class="pl-k">as</span> <span class="pl-s1">tfds</span>
<span class="pl-k">import</span> <span class="pl-s1">tensorflow_recommenders</span> <span class="pl-k">as</span> <span class="pl-s1">tfrs</span>

<span class="pl-c"># Ratings data.</span>
<span class="pl-s1">ratings</span> <span class="pl-c1">=</span> <span class="pl-s1">tfds</span>.<span class="pl-en">load</span>(<span class="pl-s">'movielens/100k-ratings'</span>, <span class="pl-s1">split</span><span class="pl-c1">=</span><span class="pl-s">"train"</span>)
<span class="pl-c"># Features of all the available movies.</span>
<span class="pl-s1">movies</span> <span class="pl-c1">=</span> <span class="pl-s1">tfds</span>.<span class="pl-en">load</span>(<span class="pl-s">'movielens/100k-movies'</span>, <span class="pl-s1">split</span><span class="pl-c1">=</span><span class="pl-s">"train"</span>)

<span class="pl-c"># Select the basic features.</span>
<span class="pl-s1">ratings</span> <span class="pl-c1">=</span> <span class="pl-s1">ratings</span>.<span class="pl-en">map</span>(<span class="pl-k">lambda</span> <span class="pl-s1">x</span>: {
    <span class="pl-s">"movie_id"</span>: <span class="pl-s1">tf</span>.<span class="pl-s1">strings</span>.<span class="pl-en">to_number</span>(<span class="pl-s1">x</span>[<span class="pl-s">"movie_id"</span>]),
    <span class="pl-s">"user_id"</span>: <span class="pl-s1">tf</span>.<span class="pl-s1">strings</span>.<span class="pl-en">to_number</span>(<span class="pl-s1">x</span>[<span class="pl-s">"user_id"</span>])
})
<span class="pl-s1">movies</span> <span class="pl-c1">=</span> <span class="pl-s1">movies</span>.<span class="pl-en">map</span>(<span class="pl-k">lambda</span> <span class="pl-s1">x</span>: <span class="pl-s1">tf</span>.<span class="pl-s1">strings</span>.<span class="pl-en">to_number</span>(<span class="pl-s1">x</span>[<span class="pl-s">"movie_id"</span>]))

<span class="pl-c"># Build a model.</span>
<span class="pl-k">class</span> <span class="pl-v">Model</span>(<span class="pl-s1">tfrs</span>.<span class="pl-v">Model</span>):

  <span class="pl-k">def</span> <span class="pl-en">__init__</span>(<span class="pl-s1">self</span>):
    <span class="pl-en">super</span>().<span class="pl-en">__init__</span>()

    <span class="pl-c"># Set up user representation.</span>
    <span class="pl-s1">self</span>.<span class="pl-s1">user_model</span> <span class="pl-c1">=</span> <span class="pl-s1">tf</span>.<span class="pl-s1">keras</span>.<span class="pl-s1">layers</span>.<span class="pl-v">Embedding</span>(
        <span class="pl-s1">input_dim</span><span class="pl-c1">=</span><span class="pl-c1">2000</span>, <span class="pl-s1">output_dim</span><span class="pl-c1">=</span><span class="pl-c1">64</span>)
    <span class="pl-c"># Set up movie representation.</span>
    <span class="pl-s1">self</span>.<span class="pl-s1">item_model</span> <span class="pl-c1">=</span> <span class="pl-s1">tf</span>.<span class="pl-s1">keras</span>.<span class="pl-s1">layers</span>.<span class="pl-v">Embedding</span>(
        <span class="pl-s1">input_dim</span><span class="pl-c1">=</span><span class="pl-c1">2000</span>, <span class="pl-s1">output_dim</span><span class="pl-c1">=</span><span class="pl-c1">64</span>)
    <span class="pl-c"># Set up a retrieval task and evaluation metrics over the</span>
    <span class="pl-c"># entire dataset of candidates.</span>
    <span class="pl-s1">self</span>.<span class="pl-s1">task</span> <span class="pl-c1">=</span> <span class="pl-s1">tfrs</span>.<span class="pl-s1">tasks</span>.<span class="pl-v">Retrieval</span>(
        <span class="pl-s1">metrics</span><span class="pl-c1">=</span><span class="pl-s1">tfrs</span>.<span class="pl-s1">metrics</span>.<span class="pl-v">FactorizedTopK</span>(
            <span class="pl-s1">candidates</span><span class="pl-c1">=</span><span class="pl-s1">movies</span>.<span class="pl-en">batch</span>(<span class="pl-c1">128</span>).<span class="pl-en">map</span>(<span class="pl-s1">self</span>.<span class="pl-s1">item_model</span>)
        )
    )

  <span class="pl-k">def</span> <span class="pl-en">compute_loss</span>(<span class="pl-s1">self</span>, <span class="pl-s1">features</span>: <span class="pl-v">Dict</span>[<span class="pl-v">Text</span>, <span class="pl-s1">tf</span>.<span class="pl-v">Tensor</span>], <span class="pl-s1">training</span><span class="pl-c1">=</span><span class="pl-c1">False</span>) <span class="pl-c1">-&gt;</span> <span class="pl-s1">tf</span>.<span class="pl-v">Tensor</span>:

    <span class="pl-s1">user_embeddings</span> <span class="pl-c1">=</span> <span class="pl-s1">self</span>.<span class="pl-en">user_model</span>(<span class="pl-s1">features</span>[<span class="pl-s">"user_id"</span>])
    <span class="pl-s1">movie_embeddings</span> <span class="pl-c1">=</span> <span class="pl-s1">self</span>.<span class="pl-en">item_model</span>(<span class="pl-s1">features</span>[<span class="pl-s">"movie_id"</span>])

    <span class="pl-k">return</span> <span class="pl-s1">self</span>.<span class="pl-en">task</span>(<span class="pl-s1">user_embeddings</span>, <span class="pl-s1">movie_embeddings</span>)


<span class="pl-s1">model</span> <span class="pl-c1">=</span> <span class="pl-v">Model</span>()
<span class="pl-s1">model</span>.<span class="pl-en">compile</span>(<span class="pl-s1">optimizer</span><span class="pl-c1">=</span><span class="pl-s1">tf</span>.<span class="pl-s1">keras</span>.<span class="pl-s1">optimizers</span>.<span class="pl-v">Adagrad</span>(<span class="pl-c1">0.5</span>))

<span class="pl-c"># Randomly shuffle data and split between train and test.</span>
<span class="pl-s1">tf</span>.<span class="pl-s1">random</span>.<span class="pl-en">set_seed</span>(<span class="pl-c1">42</span>)
<span class="pl-s1">shuffled</span> <span class="pl-c1">=</span> <span class="pl-s1">ratings</span>.<span class="pl-en">shuffle</span>(<span class="pl-c1">100_000</span>, <span class="pl-s1">seed</span><span class="pl-c1">=</span><span class="pl-c1">42</span>, <span class="pl-s1">reshuffle_each_iteration</span><span class="pl-c1">=</span><span class="pl-c1">False</span>)

<span class="pl-s1">train</span> <span class="pl-c1">=</span> <span class="pl-s1">shuffled</span>.<span class="pl-en">take</span>(<span class="pl-c1">80_000</span>)
<span class="pl-s1">test</span> <span class="pl-c1">=</span> <span class="pl-s1">shuffled</span>.<span class="pl-en">skip</span>(<span class="pl-c1">80_000</span>).<span class="pl-en">take</span>(<span class="pl-c1">20_000</span>)

<span class="pl-c"># Train.</span>
<span class="pl-s1">model</span>.<span class="pl-en">fit</span>(<span class="pl-s1">train</span>.<span class="pl-en">batch</span>(<span class="pl-c1">4096</span>), <span class="pl-s1">epochs</span><span class="pl-c1">=</span><span class="pl-c1">5</span>)

<span class="pl-c"># Evaluate.</span>
<span class="pl-s1">model</span>.<span class="pl-en">evaluate</span>(<span class="pl-s1">test</span>.<span class="pl-en">batch</span>(<span class="pl-c1">4096</span>), <span class="pl-s1">return_dict</span><span class="pl-c1">=</span><span class="pl-c1">True</span>)</pre><div class="zeroclipboard-container">

  </div></div>
</article></div>
