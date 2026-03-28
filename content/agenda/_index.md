---
title: 

# Listing view
view: compact
---

<section class="qbt-agenda">
  <style>
  .qbt-agenda {
    max-width: 960px;
  }
  .qbt-agenda h2,
  .qbt-agenda .agenda-item[id] {
    scroll-margin-top: 90px;
  }
  .qbt-agenda h2 {
    margin-top: 2rem;
    padding-bottom: 0.35rem;
    border-bottom: 1px solid #ddd;
  }
  .qbt-agenda .agenda-nav {
    margin: 0.75rem 0 1.25rem;
    padding: 0.7rem 0.8rem;
    border: 1px solid #ddd;
    border-radius: 8px;
    background: #fafafa;
  }
  .qbt-agenda .agenda-nav p {
    margin: 0 0 0.45rem;
  }
  .qbt-agenda .agenda-nav p:last-child {
    margin-bottom: 0;
  }
  .qbt-agenda .agenda-nav strong {
    display: inline-block;
    margin-right: 0.35rem;
  }
  .qbt-agenda .agenda-nav-day {
    display: block;
    margin: 0.2rem 0;
    font-weight: 600;
  }
  .qbt-agenda .agenda-nav-group {
    display: block;
    margin: 0.35rem 0;
  }
  .qbt-agenda .agenda-nav-group-label {
    display: block;
    margin-bottom: 0.2rem;
    font-weight: 600;
  }
  .qbt-agenda .agenda-nav a {
    display: inline-block;
    margin: 0.1rem 0.22rem 0.1rem 0;
    padding: 0.18rem 0.42rem;
    border-radius: 999px;
    background: #eef3f8;
    text-decoration: none;
    line-height: 1.25;
  }
  .qbt-agenda .agenda-nav a:hover,
  .qbt-agenda .agenda-nav a:focus {
    background: #dce8f5;
    text-decoration: underline;
  }
  .qbt-agenda .agenda-item {
    display: grid;
    grid-template-columns: 140px 1fr;
    gap: 1rem;
    margin: 0.85rem 0;
  }
  .qbt-agenda .agenda-time {
    font-weight: 600;
    white-space: nowrap;
  }
  .qbt-agenda .agenda-content ul {
    margin: 0.4rem 0 0 1.2rem;
  }
  @media (max-width: 700px) {
    .qbt-agenda .agenda-item {
      grid-template-columns: 1fr;
      gap: 0.3rem;
    }
    .qbt-agenda .agenda-time {
      margin-bottom: 0.1rem;
    }
  }
  </style>

  <h1>Workshop Agenda</h1>

  <div class="agenda-nav">
    <p><strong>Days</strong></p>
    <a class="agenda-nav-day" href="#wednesday-april-8">Wednesday, April 8</a>
    <a class="agenda-nav-day" href="#thursday-april-9">Thursday, April 9</a>
    <a class="agenda-nav-day" href="#friday-april-10">Friday, April 10</a>
    <div class="agenda-nav-group">
      <span class="agenda-nav-group-label">Wednesday Sessions</span>
      <a href="#session-1">Session 1: Nexus of Quantum Technology and Biology</a>
      <a href="#session-2">Session 2: Quantum in Biology</a>
      <a href="#session-3">Session 3: Quantum Biosensors</a>
      <a href="#session-4">Session 4: Health</a>
    </div>
    <div class="agenda-nav-group">
      <span class="agenda-nav-group-label">Thursday Sessions</span>
      <a href="#session-5">Session 5: Quantum Phenomena</a>
      <a href="#session-6">Session 6: Quantum Biosensors 2</a>
      <a href="#session-7">Session 7: Spin-Based Quantum Biosensors</a>
    </div>
    <div class="agenda-nav-group">
      <span class="agenda-nav-group-label">Friday Sessions</span>
      <a href="#session-8">Session 8: Photonic Quantum Sensing</a>
      <a href="#session-9">Session 9: Quantum Centers &amp; Tech. Transfer</a>
    </div>
  </div>

  <h2 id="wednesday-april-8">Wednesday, April 8</h2>

  <div class="agenda-item">
    <div class="agenda-time">8:15 AM</div>
    <div class="agenda-content">Breakfast</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">9:00 AM</div>
    <div class="agenda-content">
      <strong>Welcoming Remarks</strong>
      <ul>
        <li>Darryl Pines (President, UMD)</li>
        <li>Pat O’Shea (VPR)</li>
        <li>Amitabh Varshney (Dean, CMNS, UMD)</li>
        <li>Welcome from NSF</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item" id="session-1">
    <div class="agenda-time">9:20 AM</div>
    <div class="agenda-content">
      <strong>Session 1: Nexus of Quantum Technology and Biology</strong><br>
      <em>Chair: Peter Maurer</em>
      <ul>
        <li><strong>9:20 AM:</strong> Workshop Aims — Wolfgang Losert (University of Maryland, Physics; IPST)</li>
        <li><strong>9:30 AM:</strong> Quantum – from Science to Impact — Gretchen Campbell (University of Maryland, Quantum Research &amp; Education)</li>
        <li><strong>10:00 AM:</strong> Cancer: The Problem of Rapid, Early, Inexpensive Diagnosis — Arnold Levine (Princeton University, Emeritus)</li>
        <li><strong>10:30 AM:</strong> Quantum Technology for Biology and Health — Lincoln Carr (Colorado School of Mines, Physics / Quantum Engineering)</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">11:00 AM</div>
    <div class="agenda-content">Break</div>
  </div>

  <div class="agenda-item" id="session-2">
    <div class="agenda-time">11:20 AM</div>
    <div class="agenda-content">
      <strong>Session 2: Quantum in Biology</strong><br>
      <em>Chair: Wolfgang Losert</em>
      <ul>
        <li><strong>11:20 AM:</strong> Quantum metrology enhanced by effective time reversal — Nicole Yunger Halpern (NIST / QuICS / JQI)</li>
        <li><strong>11:40 AM:</strong> Quantum Control, Hyperpolarisation &amp; Signal Processing for Quantum Sensing in the Life Sciences — Martin Plenio (Ulm University)</li>
        <li><strong>12:00 PM:</strong> Qubits at room temperature — Peter Maurer (University of Chicago, PME)</li>
        <li><strong>12:20 PM:</strong> Mechanism of magnetic field effect in mScarlet3 — Katherine Xiang (Harvard University)</li>
        <li><strong>12:40 PM:</strong> Roundtable Discussions</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">1:00–2:00 PM</div>
    <div class="agenda-content">
      <strong>Lunch &amp; Roundtable Discussions on Biological &amp; Medical Opportunities</strong>
      <p>Attendees are encouraged to move between tables; each table has a discussion leader and student scribe.</p>
      <ul>
        <li>Tracking Molecular Interactions (Molecular Biophysics) — Don Lamb, LMU Munich</li>
        <li>Cell Signaling — José Onuchic, Rice</li>
        <li>Clinical Imaging — Michele Dougherty, Mayo Clinic</li>
        <li>Cell Mechanics — Maria Mukhina, UMD</li>
        <li>Immune System and Cancer — Arnold Levine, Princeton</li>
        <li>Aging — Kan Cao, UMD</li>
        <li>Tendon Disorders — Catherine Kuo, UMD</li>
        <li>Oncology — Ken Pienta, JHU</li>
        <li>Continuous monitoring in biology and medicine — Aditya Rajagopal, Caltech</li>
        <li>BRAIN Initiative topic 1 — Grace Hwang, NIH</li>
        <li>BRAIN Initiative topic 2 — Joe Monaco, NIH</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item" id="session-3">
    <div class="agenda-time">2:00 PM</div>
    <div class="agenda-content">
      <strong>Session 3: Quantum Biosensors</strong><br>
      <em>Chairs: Warwick Bowen (University of Queensland, ARC Centre for Quantum Biotechnology); Prineha Narang (UCLA, Physical Sciences; ECE)</em>
      <ul>
        <li>Quantum Diamond NMR Microscopy for Biochemical Analysis — John Blanchard (UMD)</li>
        <li>Quantum Biomechanics — Vladislav Yakovlev (Texas A&amp;M University)</li>
        <li>Engineered Proteins for Quantum Sensing and Actuation in Cells — Yun Chen (JHU)</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">3:20 PM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">3:40 PM</div>
    <div class="agenda-content">Break</div>
  </div>

  <div class="agenda-item" id="session-4">
    <div class="agenda-time">4:00 PM</div>
    <div class="agenda-content">
      <strong>Session 4: Health</strong><br>
      <em>Chairs: Krastan Blagoev; José Onuchic (Rice University); Catherine Kuo (UMD); Ken Pienta (JHU)</em>
      <ul>
        <li>Solving an Unsolved Biomedical Problem with First-Principles Physics: Measuring True Non-invasive, Continuous Blood Pressure — Aditya Rajagopal, Caltech</li>
        <li>Advancing Brain-Computer Interfaces to Improve Health with Quantum Technologies — Mikolaj A. Wieczorek (Mayo Clinic Florida) and Michele Dougherty (Mayo Clinic)</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">5:40 PM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">6:00 PM</div>
    <div class="agenda-content">Poster session and buffet</div>
  </div>

  <h2 id="thursday-april-9">Thursday, April 9</h2>

  <div class="agenda-item">
    <div class="agenda-time">8:15 AM</div>
    <div class="agenda-content">Breakfast</div>
  </div>

  <div class="agenda-item" id="session-5">
    <div class="agenda-time">9:00 AM</div>
    <div class="agenda-content">
      <strong>Session 5: Quantum Phenomena</strong><br>
      <em>Chair: Nicole Yunger Halpern</em>
      <ul>
        <li>Organizing Quantum Biology — Clarice Aiello (Quantum Biology Institute)</li>
        <li>Dynamics of cellular processes through live-cell imaging — Stoyno Stoynov (Institute of Molecular Biology, Coordinator of Sofia Euro-BioImaging Node)</li>
        <li>Questions and Approaches in Molecular Single Molecule Biophysics — Don Lamb (LMU Munich, Chemistry)</li>
        <li>Isotopic effects in neural functioning — Zoya Leonenko (University of Waterloo)</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">10:20 AM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">10:40 AM</div>
    <div class="agenda-content">Break</div>
  </div>

  <div class="agenda-item" id="session-6">
    <div class="agenda-time">11:00 AM</div>
    <div class="agenda-content">
      <strong>Session 6: Quantum Biosensors 2</strong><br>
      <em>Chair: Don Lamb</em>
      <ul>
        <li>NV Diamond — Andrea Candini (CNR-ISOF, Italy)</li>
        <li>Bringing multiplexed ultrasensitive diagnostics to near-patient use with quantum sensing — Colin Connolly</li>
        <li>Topic TBD — Alexander Pearson (University of Chicago Medicine)</li>
        <li>TBA industry</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">12:20 PM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">12:40–2:00 PM</div>
    <div class="agenda-content">
      <strong>Lunch &amp; Roundtable Discussions on Biological &amp; Medical Opportunities</strong>
      <p>Attendees are encouraged to move between tables; each table has a discussion leader, funder, and student scribe.</p>
      <ul>
        <li>Medical Oncology — Alexander Pearson, University of Chicago Medicine</li>
        <li>Tracking Molecular Interactions (Molecular Biophysics) — Don Lamb, LMU</li>
        <li>Cell Signaling — José Onuchic, Rice</li>
        <li>Clinical Imaging — Michele Dougherty, Mayo Clinic</li>
        <li>Cell Mechanics — Maria Mukhina, UMD</li>
        <li>Immune System and Cancer — Arnold Levine, Princeton</li>
        <li>Tendon Disorders — Catherine Kuo, UMD</li>
        <li>Oncology — Ken Pienta</li>
        <li>BRAIN Initiative topic 1 — Grace Hwang, NIH</li>
        <li>BRAIN Initiative topic 2 — Joe Monaco, NIH</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item" id="session-7">
    <div class="agenda-time">2:00 PM</div>
    <div class="agenda-content">
      <strong>Session 7: Spin-Based Quantum Biosensors</strong><br>
      <em>Chair: Ronald L. Walsworth</em>
      <ul>
        <li>NV Ensemble Magnetic Field Imaging via Laser Raster Scanning — Alexander Huck (Technical University of Denmark)</li>
        <li>Early Detection of Alzheimer’s Disease Risk by Monolayer Quantum Materials — Cheng Gong (University of Maryland)</li>
        <li>Topic TBD — Songi Han</li>
        <li>Quantum Magnetometers for Biosensing Applications — Birol Ozturk (Morgan State)</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">3:20 PM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">3:40 PM</div>
    <div class="agenda-content">Break</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">4:00 PM</div>
    <div class="agenda-content">
      <strong>Funders Panel</strong><br>
      <em>Moderator: Krastan Blagoev (NSF)</em>
      <ul>
        <li>Quantum Biomedical Innovation and Technologies — Geetha Senthil (NIH)</li>
        <li>Robert Lambeth (ARL)</li>
        <li>TBA</li>
        <li>TBA</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">6:00 PM</div>
    <div class="agenda-content">Conference Dinner</div>
  </div>

  <h2 id="friday-april-10">Friday, April 10</h2>

  <div class="agenda-item">
    <div class="agenda-time">8:15 AM</div>
    <div class="agenda-content">Breakfast</div>
  </div>

  <div class="agenda-item" id="session-8">
    <div class="agenda-time">9:00 AM</div>
    <div class="agenda-content">
      <strong>Session 8: Photonic Quantum Sensing</strong><br>
      <em>Chair: Avik Dutt</em>
      <ul>
        <li>Sensing based on entangled two-photon absorption — George Schatz (Northwestern University)</li>
        <li>Topic TBD — John T. Fourkas (University of Maryland, Chemistry &amp; Biochemistry; IPST)</li>
        <li>Collective quantum phenomena at room temperature — Peter Littlewood (University of Chicago, Physics; James Franck Institute)</li>
        <li>Topic TBD — Qizhong Liang</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">10:20 AM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">10:40 AM</div>
    <div class="agenda-content">Break</div>
  </div>

  <div class="agenda-item" id="session-9">
    <div class="agenda-time">11:00 AM</div>
    <div class="agenda-content">
      <strong>Session 9: Quantum Centers &amp; Tech. Transfer</strong><br>
      <em>Chair: Gretchen Campbell</em>
      <ul>
        <li>Topic TBD — David Awschalom (University of Chicago, PME; Argonne National Laboratory)</li>
        <li>Quantum-enhanced and Quantum-limited biological imaging technologies — Warwick Bowen (University of Queensland, ARC Centre for Quantum Biotechnology)</li>
        <li>Quantum Technology Center — Ronald L. Walsworth</li>
      </ul>
    </div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">12:00 PM</div>
    <div class="agenda-content">Roundtable Discussions</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">12:30 PM</div>
    <div class="agenda-content">End of conference</div>
  </div>

  <div class="agenda-item">
    <div class="agenda-time">1:00–4:00 PM</div>
    <div class="agenda-content">Advisory Board Working Session</div>
  </div>
</section>
