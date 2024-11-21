# Index of GitHub Repositories

Here you can explore GitHub repositories associated with SyNergy projects, and links to their related publications.

_For more information on our research and publications, visit [the SyNergy website](https://synergy-munich.de/)._

<br>
<details>
  <summary>
    <h2><span class="arrow">&#9654;</span> Transcriptomics Projects</h2>
  </summary>

  <hr>
  <div>
    <h3>Adult neural stem cell activation in mice is regulated by the day/night cycle and intracellular calcium dynamics</h3>
    <p>
      <a href="https://www.cell.com/cell/fulltext/S0092-8674(20)31748-7">
        <img src="assets/img/thumbnails/t1.png" alt="Thumbnail" />
      </a>
    </p>
    <ul>
      <li>
        <a href="https://github.com/SaghatelyanLab/Calcium_analysis_in_NSC">Code for analysis of Ca2+ activity in neural stem cells</a>
      </li>
    </ul>
    <hr>

    <h3>CD8+ T cells induce interferon-responsive oligodendrocytes and microglia in white matter aging</h3>
    <p>
      <a href="https://www.nature.com/articles/s41593-022-01183-6">
        <img src="assets/img/thumbnails/t2.png" alt="Thumbnail" />
      </a>
    </p>
    <ul>
      <li>
        <a href="https://github.com/ISD-SystemsNeuroscience/Aging_Oligos_Microglia">Transcriptomics characterization of oligodendrocytes and microglia in white matter aging</a>
      </li>
    </ul>
    <hr>

    <h3>Parkinson's disease motor symptoms rescue by CRISPRa‐reprogramming astrocytes into GABAergic neurons</h3>
    <p>
      <a href="https://www.embopress.org/doi/full/10.15252/emmm.202114797">
        <img src="assets/img/thumbnails/t3.png" alt="Thumbnail" />
      </a>
    </p>
    <ul>
      <li>
        <a href="https://github.com/theislab/astrocytes_reprogramming_analysis">Astrocytes reprogramming analysis</a>
      </li>
    </ul>
  </div>

  <div class="show-more">
    <hr>
    <h3>Phagocyte-mediated synapse removal in cortical neuroinflammation is promoted by local calcium accumulation</h3>
    <p>
      <a href="https://www.nature.com/articles/s41593-020-00780-7">
        <img src="assets/img/thumbnails/t4.png" alt="Thumbnail" />
      </a>
    </p>
    <ul>
      <li>
        <ul>
          <li>
            <a href="https://github.com/portugueslab/Jafari-et-al-2020">Code and sample data used for parts of the analysis in the paper Jafari et al., 2020</a>
          </li>
          <li>
            <a href="https://github.com/engelsdaniel/schirmer_reanalyzed">Re-analysis of snRNA-seq data from Schirmer et al., Nature, 2019</a>
          </li>
        </ul>
      </li>
    </ul>
    <hr>

    <h3>Shared inflammatory glial cell signature after stab wound injury</h3>
  <p>
    <a href="https://www.nature.com/articles/s41467-024-46625-w">
      <img src="assets/img/thumbnails/t5.png" alt="Thumbnail" />
    </a>
  </p>
  <p>
  <ul>
    <li>
      <ul>
        <li>
          <a href="https://github.com/NinkovicLab/Koupourtidou-Schwarz-et-al">Analysis pipeline for scRNA-seq/stRNA-seq</a>
        </li>
        <li>
          <a href="https://github.com/isdneuroimaging/mmqt">Microglia morphology quantification tool (MMQT)</a>
        </li>
        <li>
          <a href="https://github.com/simonmfr/SPATA2/tree/publicationCK">Spatial gradient analysis</a>
        </li>
      </ul>
    </li>
  </ul>
  </p>
  <hr>

  <h3>Spatial Transcriptomics-correlated Electron Microscopy maps transcriptional and ultrastructural responses to brain injury</h3>
  <p>
    <a href="https://www.nature.com/articles/s41467-023-39447-9">
      <img src="assets/img/thumbnails/t6.png" alt="Thumbnail" />
    </a>
  </p>
  <p>
  <ul>
    <li>
      <a href="https://github.com/ISD-SystemsNeuroscience/STcEM">Spatial Transcriptomics-correlated Electron Microscopy analysis</a>
    </li>
  </ul>
  </p>
  <hr>

  <h3>T cell-mediated microglial activation triggers myelin pathology in a mouse model of amyloidosis</h3>
  <p>
    <a href="https://www.nature.com/articles/s41593-024-01682-8">
      <img src="assets/img/thumbnails/t7.png" alt="Thumbnail" />
    </a>
  </p>
  <p>
  <ul>
    <li>
      <a href="https://github.com/Ruoqing-feng/AD_inflammation">scRNA-seq analysis</a>
    </li>
  </ul>
  </p>
  <hr>

  <h3>T cells modulate the microglial response to brain ischemia</h3>
  <p>
    <a href="https://elifesciences.org/articles/82031">
      <img src="assets/img/thumbnails/t8.png" alt="Thumbnail" />
    </a>
  </p>
  <p>
  <ul>
    <li>
      <a href="https://github.com/Lieszlab/Benakis-et-al.-2022-eLife">scRNA-seq analysis</a>
    </li>
  </ul>
  <p>

    <!-- Add remaining items similarly -->
  </div>

  <button class="toggle-button" onclick="toggleVisibility(this)">Show More</button>
</details>

<script>
  function toggleVisibility(button) {
    const showMoreSection = button.previousElementSibling;
    if (showMoreSection.style.display === "none") {
      showMoreSection.style.display = "block";
      button.textContent = "Show Less";
    } else {
      showMoreSection.style.display = "none";
      button.textContent = "Show More";
    }
  }
</script>

<style>
  .show-more {
    display: none;
  }

  .toggle-button {
    display: block;
    margin: 10px auto;
    padding: 5px 15px;
    background-color: #007bff;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }

  .toggle-button:hover {
    background-color: #0056b3;
  }
</style>
