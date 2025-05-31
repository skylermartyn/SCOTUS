<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academic Article Layout</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            background-color: #fafafa;
        }

        .container {
            display: flex;
            height: 100vh;
            max-width: 1400px;
            margin: 0 auto;
            background: white;
            box-shadow: 0 0 20px rgba(0,0,0,0.1);
        }

        /* Table of Contents - Left Column */
        .toc {
            width: 300px;
            background: #f8f9fa;
            border-right: 2px solid #e9ecef;
            padding: 20px;
            overflow-y: auto;

            position: sticky;
            top: 0;
            height: 100vh;
            transition: all 0.3s ease;
        }

        .toc-items-container {
            transition: margin-top 0.5s ease;
        }

        .toc-items-container.shifted {
            margin-top: 130px;
        }

        .toc::-webkit-scrollbar {
            display: none;
        }

        .toc h3 {
            margin-bottom: 15px;
            color: #2c3e50;
            font-size: 18px;
            border-bottom: 2px solid #c14335;
            padding-bottom: 8px;
            transition: opacity 0.5s ease;
        }

        .toc h3.hidden {
            opacity: 0;
            pointer-events: none;
            padding-bottom: 20px;

        }

        .floating-header {
            position: absolute;
            top: 20px;
            left: 20px;
            right: 20px;
            margin-bottom: 20px;
            opacity: 0;
            transition: opacity 0.5s ease;
            pointer-events: none;
            z-index: 5;
        }

        .floating-header.visible {
            opacity: 1;
            pointer-events: auto;      /* ← allow clicks when visible */
            cursor: pointer;           /* ← show the hand cursor */
        }

        .floating-header h1 {
            color: #2c3e50;
            font-size: 1.4em;
            line-height: 1.2;
            margin-bottom: 5px;
        }

        .floating-header .subtitle {
            color: #7f8c8d;
            font-size: 0.9em;
            font-style: italic;
            margin-bottom: 15px;
            padding-bottom: 8px;
            border-bottom: 2px solid #c14335;
        }

        .toc-item {
            margin-bottom: 10px;
            cursor: pointer;
            padding: 8px 12px;
            border-radius: 4px;
            transition: all 0.2s ease;
            color: #495057;
        }

        .toc-item:hover {
            background: #e9ecef;
            color: #2c3e50;
        }

        .toc-item.active {
            background: #c14335;
            color: white;
        }

        .toc-nested {
            margin-left: 20px;
            font-size: 14px;
            transition: all 0.3s ease;
        }

        .toc-toggle {
            display: inline-block;
            width: 20px;
            cursor: pointer;
            font-weight: bold;
            color: #6c757d;
            transition: all 0.3s ease;
        }

        .toc-nested.collapsed {
            display: none;
            transition: all 0.3s ease;
        }

        /* Main Content - Center Column */
        .content {
            flex: 1;
            padding: 0px 90px;
            padding-bottom: 60px;;
            overflow-y: auto;
            max-height: 100vh;
            scrollbar-width: none; /* Firefox */
            -ms-overflow-style: none; /* IE/Edge */
        }

        .content::-webkit-scrollbar {
            display: none; /* Chrome/Safari/Opera */
        }

        .content h1, .content .subtitle {
            margin-left: -50px;
            margin-right: -50px;
        }

        .content h1 {
            color: #2c3e50;
            margin-bottom: 20px;
            font-size: 2.5em;
            line-height: 1.2;
            padding-top: 60px;
        }

        .content .subtitle {
            color: #7f8c8d;
            font-size: 1.2em;
            margin-bottom: 20px;
            font-style: italic;
        }

        .content h2 {
            color: #2c3e50;
            margin: 30px 0 15px 0;
            font-size: 1.8em;
            border-bottom: 1px solid #bdc3c7;
            padding-bottom: 5px;
        }


        .content h3 {
            color: #2c3e50;
            margin: 25px 0 60px 0;
            font-size: 1.8em;
            position: sticky;
            top: 0;
            vertical-align: baseline;
            background: white;
            z-index: 10;
            padding-top: 40px;
            padding-bottom: 15px;
            width: 100%;
            border-bottom: 1px solid #bdc3c7;
            box-shadow: 0 0 10px 10px rgba(255, 255, 255, 0.8),   /* Blurred inner shadow */
                0 0 20px 20px rgba(255, 255, 255, 0.6),   /* More blur, less opacity */
                0 0 30px 30px rgba(255, 255, 255, 0.4),   /* Even more blur */
                0 0 40px 40px rgba(255, 255, 255, 0.2),   /* Most blur, least opacity */
                0 0 45px 45px rgba(255, 255, 255, 0.1);   /* Outermost glow */
        }




        .fade-box {
            content: '';
            display: block;
            width: 100%;
            height: 10px;
            background: linear-gradient(to bottom, rgb(255, 255, 255, 1), rgba(255, 255, 255, 0));
        }
        
        .content p {
            font-size: 12pt;
            line-height: 24pt;
           /* margin-bottom: 15px;*/
            text-align: justify;
            text-indent: 50px;
            hyphens: auto;
            color: #000000;
        }

        .content p.cont {
            text-indent: 0px;
        }

        blockquote {
            margin: 20px;
            margin-bottom: 35px;
            padding: 30px 30px 30px 30px;
            color: #000b0c;
            line-height: 1.6;
            /*align-self: center;*/
            display: inline-block;
            background-color: #f4e7ce;
            box-shadow: 0 5px 10px rgba(0,0,0,0.35);
            
        }

        .fn-ref {
            color: #3498db;
            text-decoration: none;
            font-size: 0.8em;
            vertical-align: top; position: relative; top: -0.5em;
            cursor: pointer;
            /*left: 5px*/
            padding: 2px 4px;
            border-radius: 3px;
            transition: background-color 0.2s ease;
        }

        .fn-ref:hover {
            background-color: #3498db;
            color: white;
        }

        .inline-icon {
            height: 4em;
            vertical-align: -4px;
            margin-right: 30px;
            margin-left: 20px;
            border-radius: 5%;
            box-shadow: 0 5px 10px rgba(0,0,0,0.35);
            transition: all 0.5s ease;
        }

        /*.inline-icon:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
            transform: scale(1.03);
            transition: all 0.5s ease;
        }*/

        .inline-banner {
            width: 100%;
            height: auto;
            margin: 20px 0;
            border-radius: 8px;
            box-shadow: 0 5px 10px rgba(0,0,0,0.35);
            transition: all 0.5s ease;
        }

        /*.inline-banner:hover {
            box-shadow: 0 10px 20px rgba(0,0,0,0.4);
            transform: scale(1.03);
            transition: all 0.5s ease;
        }*/

        .fake-icon {
            height: 4em;
            vertical-align: baseline;
            margin-right: 20px;
            margin-left: 20px;
            border-radius: 5%;
            background: white;
        }

        h3.conclusion {
            background-color: unset;
            text-align: center;
            color: rgb(254, 248, 231);
            height: 400px;
            background-image: url('https://www.supremecourt.gov/visiting/exhibitions/GroupPhotoExhibit/images/2022-31-8_8x10.jpg');
            background-size: 100% auto;
            border-radius: 8px;
            top: 30px;
            box-shadow: 0 0 10px 10px rgba(255, 255, 255, 0.8),   /* Blurred inner shadow */
                0 0 20px 20px rgba(255, 255, 255, 0.6),   /* More blur, less opacity */
                0 0 30px 30px rgba(255, 255, 255, 0.4),   /* Even more blur */
                0 0 40px 40px rgba(255, 255, 255, 0.2),   /* Most blur, least opacity */
                0 0 50px 50px rgba(255, 255, 255, 0.1);   /* Outermost glow */
            letter-spacing: 0.2rem;
        }

        .scroll-anchor {
            position: relative;
            top: -40px; /* Offset to account for sticky header padding */
            visibility: hidden;
            height: 0;
        }


        /* Container for the list */
.methodology-list {
    line-height: 1.6;
    color: #333;
    max-width: 800px;
    margin: 0 auto;
}

/* Ordered list styling */
.methodology-list ol {
    list-style: none;
    counter-reset: item;
    padding-left: 0;
    margin: 20px 0;
}

/* List items */
.methodology-list li {
    counter-increment: item;
    margin-bottom: 30px;
    padding-left: 60px;
    font: 12pt;
    line-height: 24pt;
    position: relative;
}

/* Numbers */
.methodology-list li::before {
    content: counter(item) ".";
    position: absolute;
    left: 0;
    top: 0;
    font-weight: bold;
    /*font-size: 1.2em;*/
    min-width: 40px;
}

/* Title styling (first part before period) */
.methodology-list .list-title {
    font-weight: 600;
    margin-right: 5px;
}

/* Regular text continues on same line */
.methodology-list .list-content {
    display: inline;
    font-weight: normal;
}

/* Table container */
.vote-forecast-table {
    width: 100%;
    max-width: 900px;
    margin: 20px auto;
    border-collapse: collapse;
    font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
    background: white;
    border: 1px solid #ddd;
    border-radius: 8px;
    overflow: hidden;
    box-shadow: 0 5px 10px rgba(0,0,0,0.35);
}

/* Table cells */
.vote-forecast-table th,
.vote-forecast-table td {
    padding: 16px 24px;
    text-align: left;
    border-bottom: 1px solid #e5e5e5;
}

/* Header styling */
.vote-forecast-table thead th {
    background-color: #f8f9fa;
    font-weight: 600;
    font-size: 18px;
    color: #333;
    border-bottom: 1px solid #ddd;
}

/* Body cell styling */
.vote-forecast-table tbody td {
    font-size: 16px;
    color: #444;
    font-weight: 400;
}

/* First column (Justice names) */
.vote-forecast-table tbody td:first-child {
    font-weight: 500;
}

/* Remove last row border */
.vote-forecast-table tbody tr:last-child td {
    border-bottom: none;
}

/* Hover effect */
.vote-forecast-table tbody tr:hover {
    background-color: #f8f9fa;
}

/* Scoreboard container */
.vote-scoreboard {
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 40px 20px;
    background: #1a1a1a;
    border-radius: 12px;
    max-width: 600px;
    margin: 30px auto;
    box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
}

/* Vintage scoreboard container */
.vote-scoreboard-vintage {
    width: 100%;
    padding: 40px 20px;
    background: #f5f3f0; /* Faded off-white */
    border: 4px solid #2a2a2a;
    border-radius: 8px;
    margin: 30px auto;
    box-shadow: 0 5px 10px rgba(0,0,0,0.35);
    position: relative;
}

/* Add vintage texture effect */
.vote-scoreboard-vintage::before {
    content: '';
    position: absolute;
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    background-image: 
        repeating-linear-gradient(
            45deg,
            transparent,
            transparent 2px,
            rgba(0, 0, 0, 0.03) 2px,
            rgba(0, 0, 0, 0.03) 4px
        );
    pointer-events: none;
}

/* Score container */
.score-container {
    display: flex;
    align-items: center;
    justify-content: center;
    gap: 30px;
    position: relative;
    z-index: 1;
}

/* Individual score items */
.score-item {
    text-align: center;
}

/* Score numbers - old-timey font style */
.score-number {
    font-size: 140px;
    font-weight: 900;
    line-height: 1;
    font-family: 'Georgia', 'Times New Roman', serif;
    text-shadow: 
        3px 3px 0 rgba(0, 0, 0, 0.2),
        1px 1px 0 rgba(0, 0, 0, 0.3);
    letter-spacing: -5px;
}

/* Darker, vintage red for against */
.score-item.against .score-number {
    color: #b71c1c;
}

/* Darker, vintage green for for */
.score-item.for .score-number {
    color: #1b5e20;
}

/* Score labels */
.score-label {
    font-size: 16px;
    font-weight: 700;
    color: #3a3a3a;
    margin-top: 15px;
    letter-spacing: 3px;
    font-family: 'Georgia', serif;
    text-transform: uppercase;
}

/* Divider */
.score-divider {
    font-size: 100px;
    color: #3a3a3a;
    font-weight: 400;
    font-family: 'Georgia', serif;
    margin: 0 20px;
    padding-bottom: 20px; /* Adjust for visual alignment */
}

/* Responsive - scales with container */
@media (max-width: 768px) {
    .score-number {
        font-size: 100px;
    }
    
    .score-divider {
        font-size: 70px;
    }
    
    .score-label {
        font-size: 14px;
        letter-spacing: 2px;
    }
    
    .score-container {
        gap: 20px;
    }
}

@media (max-width: 480px) {
    .score-number {
        font-size: 70px;
    }
    
    .score-divider {
        font-size: 50px;
        margin: 0 10px;
    }
    
    .score-label {
        font-size: 12px;
    }
    
    .vote-scoreboard-vintage {
        padding: 30px 15px;
    }
}

/* Alternative minimal version */
.vote-scoreboard-minimal {
    font-size: 100px;
    font-weight: 800;
    text-align: center;
    font-family: 'Arial Black', sans-serif;
    margin: 40px auto;
}

.vote-scoreboard-minimal .against {
    color: #dc3545;
}

.vote-scoreboard-minimal .for {
    color: #28a745;
}

/* Responsive */
@media (max-width: 768px) {
    .vote-forecast-table th,
    .vote-forecast-table td {
        padding: 12px 16px;
        font-size: 14px;
    }
}

        /* Footnotes - Right Column */
        .footnotes {
            width: 280px;
            background: #f8f9fa;
            border-left: 2px solid #e9ecef;
            padding: 0px 20px 20px 20px;
            overflow-y: auto;
            max-height: 100vh;
            position: relative;
            scrollbar-width: thin; /* Firefox */
            scrollbar-color: rgba(0,0,0,0.3) transparent;
            padding-bottom: 100vh;
        }
        

        .footnotes::-webkit-scrollbar {
            width: 8px;
        }

        .footnotes::-webkit-scrollbar-track {
            background: transparent;
        }

        .footnotes::-webkit-scrollbar-thumb {
            background-color: rgba(0,0,0,0.3);
            border-radius: 4px;
            border: none;
        }

        .footnotes::-webkit-scrollbar-thumb:hover {
            background-color: rgba(0,0,0,0.5);
        }

        .footnotes h3 {
            margin-bottom: 15px;
            color: #2c3e50;
            font-size: 16px;
            border-bottom: 2px solid #3498db;
            padding-bottom: 8px;
            padding-top: 20px;
            position: sticky;
            top: 0;
            background: rgba(248, 249, 250, 0.7);
            backdrop-filter: blur(5px);
            z-index: 10;
        }

        .footnote {
            margin-bottom: 15px;
            padding: 10px;
            background: white;
            border-radius: 4px;
            border-left: 3px solid #3498db;
            font-size: 13px;
            line-height: 1.5;
            transition: all 0.3s ease;
            opacity: 0.8;
            transform: translateX(0);
            box-shadow: 0 0 10px rgba(0,0,0,0.2);
            font-style: normal;
        }

        .footnote.highlighted {
            opacity: 1;
            transform: translateX(5px);
            box-shadow: 0 4px 12px #3498db;
        }

        .extended-footnote {
            margin-bottom: 15px;
            padding: 10px;
            background: white;
            border-radius: 4px;
            border-left: 3px solid #3498db;
            font-size: 13px;
            line-height: 1.5;
            transition: all 0.5s ease;
            opacity: 0.8;
            transform: translateX(0);
            cursor: pointer;
            overflow: hidden;
            max-height: calc(1.5em * 4 + 20px);
            position: relative;
            mask-image: linear-gradient(to bottom, white 90% , transparent)
            

        }

        .extended-footnote.highlighted {
            opacity: 1;
            transform: translateX(5px);
            box-shadow: 0 4px 12px #3498db;
            transition: all 0.5s ease;
            box-shadow: 0 4px 12px #3498db;

        }

        .extended-footnote.expanded {
            max-height: none;
            transition: all 0.5s ease;
            box-shadow: 0 4px 12px #3498db;
            mask-image: unset;
        }

        .extended-footnote:not(.expanded)::after {
            content: "° ° °";
            position: absolute;
            bottom: 10px;
            right: 10px;
            background: linear-gradient(to right, transparent, white 20%);
            padding-left: 20px;
        }

        .footnote-number {
            color: #3498db;
            font-weight: bold;
            margin-right: 5px;
        }

        

        /* Responsive Design */
        @media (max-width: 1200px) {
            .toc {
                width: 250px;
            }
            .footnotes {
                width: 240px;
            }
        }

        @media (max-width: 900px) {
            .container {
                flex-direction: column;
                height: auto;
            }
            
            .toc, .footnotes {
                width: 100%;
                height: auto;
                position: static;
            }
            
            .content {
                max-height: none;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="sticky-overlay" id="sticky-overlay"></div>
        <!-- Table of Contents -->
        <div class="toc">
            <div class="floating-header" id="floating-header">
                <h1>Predicting the Supreme Court's Ruling on Trump's Birthright Citizenship Order</h1>
                <div class="subtitle">Skyler Owen Martyn | May 29, 2025</div>
            </div>
            
            <h3>Table of Contents</h3>
            <div class="toc-items-container" id="toc-items-container">
            <div class="toc-item active" data-target="introduction-anchor">
                Introduction
            </div>
            <div class="toc-item" data-target="background-anchor">
                Background
            </div>
            <div class="toc-item" data-target="votes-anchor">
                <span class="toc-toggle">▼</span>Counting the Votes
            </div>
            <div class="toc-nested">
                <div class="toc-item" data-target="roberts-anchor">John G. Roberts, Jr.</div>
                <div class="toc-item" data-target="thomas-anchor">Clarence Thomas</div>
                <div class="toc-item" data-target="alito-anchor">Samuel A. Alito, Jr.</div>
                <div class="toc-item" data-target="sotomayor-anchor">Sonia Sotomayor</div>
                <div class="toc-item" data-target="kagan-anchor">Elena Kagan</div>
                <div class="toc-item" data-target="gorsuch-anchor">Neil M. Gorsuch</div>
                <div class="toc-item" data-target="kavanaugh-anchor">Brett M. Kavanaugh</div>
                <div class="toc-item" data-target="barrett-anchor">Amy Coney Barrett</div>
                <div class="toc-item" data-target="jackson-anchor">Ketanji Brown Jackson</div>
            </div>
            <div class="toc-item" data-target="conclusion-anchor">Conclusion</div>
            </div>
        </div>

        <!-- Main Content -->
        <div class="content" id="main-content">
            <h1 style="text-align: center;">Predicting the Supreme Court's Ruling on Trump's Birthright Citizenship Order</h1>
            <div class="subtitle" style="text-align: center;">Skyler Owen Martyn</div>
            <div class="subtitle" style="text-align: center; margin-bottom: 30px;" >May 24, 2025</div>

            <h3 id="introduction">Introduction</h3>
            <div class="scroll-anchor" id="introduction-anchor"></div>
            <p>A Civil War-era promise meets a modern executive order: does “subject to the jurisdiction thereof” shelter every child born on U.S. soil, or can Executive Order 14160 carve out those whose parents lack lawful status? Roberts, Sotomayor, Kagan, Gorsuch, Kavanaugh, and Jackson line up on one side; Thomas, Alito, and Barrett stand on the other. Tally those six votes, and the order is headed for the shredder.</p>
            <p>Section 1 of the Fourteenth Amendment sounds simple enough:</p> 
            <blockquote>"All persons born or naturalized in the United States, and subject to the jurisdiction thereof, are citizens of the United States."<a href="#fn1" class="fn-ref">1</a></blockquote>
            <p class="cont">Yet a century-and-a-half of constitutional oxygen still leaves one stubborn riddle: Who, exactly, is “subject to the jurisdiction” of the United States? President Trump’s Executive Order 14160 answers that question one way—excluding the future children of undocumented or merely temporary visitors—while the challengers say the text, history, and precedents say something very different. The Court now must decide whether the Citizenship Clause is a bright-line guarantee or a consent-based invitation.</p>
        <h3 id="background">Background</h3>
        <div class="scroll-anchor" id="background-anchor"></div>
        <p><b>The Executive Order:</b> On January 20 2025, the President signed EO 14 160, Protecting the Meaning and Value of American Citizenship. The Order declares that birth-right citizenship does not extend to a child whose mother is (1) unlawfully present, or (2) lawfully present only “temporarily,” unless the father is a citizen or lawful-permanent resident. Agencies are instructed to deny passports, Social-Security numbers, and other proofs of citizenship to those newborns, with the policy scheduled to take effect thirty days after the signing date.<a href="#fn2" class="fn-ref">2</a></p>
        
        <p><b>The Lawsuits:</b> Three days later, Washington, Arizona, Illinois, and Oregon—joined soon after by individual expectant mothers—filed suit in the Western District of Washington, alleging violations of both the Citizenship Clause and 8 U.S.C. § 1401. Judge John C. Coughenour granted a temporary restraining order on January 23 and, after briefing and argument, issued a nationwide preliminary injunction on February 6 2025.<a href="#fn3" class="fn-ref">3</a> The Government’s emergency stay application was deffered in the pending oral arguments in the Supreme Court, leaving the injunction in place while merits briefing proceeds.<a href="#fn4" class="fn-ref">4</a></p>

 <p><b>The Competing Briefs:</b> Because parallel challenges in Maryland and Massachusetts produced similar nationwide orders, the Government pressed the High Court to pare back universal relief—a request the Justices could resolve alongside the merits. For present purposes, however, the question before the Court remains elemental: does the EO square with, or shred, the Citizenship Clause as construed in <em>United States v. Wong Kim Ark</em><a href="#fn5" class="fn-ref">5</a> and its progeny?</p>


        <h3 id="votes">Counting the Votes</h3> 
        <div class="scroll-anchor" id="votes-anchor"></div> 

         <img src="https://www.supremecourt.gov/visiting/exhibitions/GroupPhotoExhibit/images/2022-31-8_8x10.jpg" alt="Supreme Court Justices" class="inline-banner">
        
        </br>
    </br>
        <p class="cont">Because this memo focuses on what the Court as a whole will do, we have to take each Justice in turn. My vote forecast applies a three-part lens:</p>
        </br>
    </br>
        <div class="methodology-list">
    <ol>
        <li>
            <span class="list-title">Methodological Fit:</span>
            <span class="list-content">I match each brief's leading themes—text, history, precedent, or practical consequences—to the Justice's own interpretive lodestars.</span>
        </li>
        <li>
            <span class="list-title">Reliance & Institutional Interests:</span>
            <span class="list-content">I weigh how dramatically the order would disrupt settled expectations, a factor that often steers the Court's middle bloc.</span>
        </li>
        <li>
            <span class="list-title">Margin for Narrow Concurrence:</span>
            <span class="list-content">Where a Justice habitually looks for a limiting principle (e.g., Barrett), I flag any narrower path that could peel off a vote without embracing the order wholesale.</span>
        </li>
    </ol>
</div>
            
         </br>
    </br>

    <p class="cont"><b>Here is a summary of the expected result:</b></p>
    <br>
    <table class="vote-forecast-table">
    <thead>
        <tr>
            <th>Justice</th>
            <th>Expected Vote</th>
            <th>Approach</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Roberts</td>
            <td style="color: rgb(194, 0, 0);">Strike EO</td>
            <td>Institutional legitimacy & stare decisis</td>
        </tr>
        <tr>
            <td>Thomas</td>
            <td style="color: green;">Uphold EO</td>
            <td>Original public meaning</td>
        </tr>
        <tr>
            <td>Alito</td>
            <td style="color: green;">Uphold EO</td>
            <td>Founding-era practice</td>
        </tr>
        <tr>
            <td>Sotomayor</td>
            <td style="color: rgb(194, 0, 0)">Strike EO</td>
            <td>Precedent & equal-protection values</td>
        </tr>
        <tr>
            <td>Kagan</td>
            <td style="color: rgb(194, 0, 0)">Strike EO</td>
            <td>Pragmatic textualism & reliance interests</td>
        </tr>
        <tr>
            <td >Gorsuch</td>
            <td style="color: rgb(194, 0, 0)">Strike EO</td>
            <td>Plain text & anti-comandeering instinct</td>
        </tr>
        <tr>
            <td>Kavanaugh</td>
            <td style="color: rgb(194, 0, 0)">Strike EO</td>
            <td>Precedent & reliance interests</td>
        </tr>
        <tr>
            <td>Barrett</td>
            <td style="color: green;">Uphold EO (narrow)</td>
            <td>Originalist with procedural focus</td>
        </tr>
        <tr>
            <td>Jackson</td>
            <td style="color: rgb(194, 0, 0)">Strike EO</td>
            <td>Reconsrtuction history & anti-caste principle</td>
        </tr>
    </tbody>
</table>
</br>
<div class="vote-scoreboard-vintage">
    <div class="score-container">
        <div class="score-item against">
            <div class="score-number">6</div>
            <div class="score-label">AGAINST</div>
        </div>
        <div class="score-divider">–</div>
        <div class="score-item for">
            <div class="score-number">3</div>
            <div class="score-label">FOR</div>
        </div>
    </div>
</div>
</br>
<br>

<p class="cont" style="font-size: 1.5em; hyphens: none; text-align: left; line-height: 30pt;"><b>The Result:</b> Donald Trump's Executive Order 14160, "Protecting The Meaning And Value Of American Citizenship," will be struck down by a majority of the Court.</p>
<br>
<br>
            <h3 id="roberts"><img src="https://www.supremecourt.gov/about/justice_pictures/Roberts_8807-16_Crop.jpg" alt="Chief Justice John G. Roberts, Jr." class="inline-icon">Chief Justice John G. Roberts, Jr.</h3>
            <div class="scroll-anchor" id="roberts-anchor"></div>
            <p>Roberts protects the Court’s institutional capital and leans on precedent whenever upheaval would damage public confidence. In <em>NFIB v. Sebelius</em>, he noted that judges “possess neither the expertise nor the prerogative to make policy judgments.”<a href="#fn6" class="fn-ref">6</a> The same caution surfaced in <em>Dep’t of Commerce v. New York</em>, where he rebuffed a “contrived” rationale for adding a census citizenship question.<a href="#fn7" class="fn-ref">7</a></p>
            
            <p>That instinct to police executive explanations will surface again when the Order tries to upend a practice cemented by <em>Wong Kim Ark</em>. Roberts has proved willing to follow precedent even when he dissented the first time around.<a href="#fn8" class="fn-ref">8</a> On citizenship, he has joined opinions applying equal protection constraints to Congress.<a href="#fn9" class="fn-ref">9</a> And his Dobbs concurrence warns against inflicting "jolt[s]" to the system with sweeping change<a href="#fn10" class="fn-ref">10</a> An executive effort to erase birth right citizenship will look to him like exactly that.</p>
            
            <p>Roberts will look first for workable administrability and institutional modesty. He is likely to find the States’ warning that the Order would produce a “geographically checkered rule of birthright citizenship” persuasive,<a href="#fn11" class="fn-ref">11</a> because it echoes his concerns in <em>Murthy v. Missouri</em> and <em>Gill v. Whitford</em> about judicially-created patchworks.<a href="#fn12" class="fn-ref">12</a> At the same time, the Government’s plea to avoid “leav[ing] Congress and the Executive Branch powerless”<a href="#fn13" class="fn-ref">13</a> to address border incentives taps his separation-of-powers instinct, as in <em>Biden v. Nebraska</em>.<a href="#fn14" class="fn-ref">14</a> Expect him to weigh those dueling institutional concerns against the clarity of <em>Wong Kim Ark’s</em> rule, which the States trumpet.</p>

            <br>
            <br>
            <h3 id="thomas"><img src="https://www.supremecourt.gov/about/justice_pictures/Thomas_9366-024_Crop.jpg" alt="Justice Clarence Thomas" class="inline-icon">Justice Clarence Thomas</h3>
            <div class="scroll-anchor" id="thomas-anchor"></div>
            <p>Thomas will revisit “subject to the jurisdiction thereof” with 1868 dictionaries in hand. He has spent decades urging restoration of original meaning.<a href="#fn15" class="fn-ref">15</a> His stance on stare decisis is blunt: when precedent is “demonstrably erroneous,” courts should discard it.<a href="#fn16" class="fn-ref">16</a></p>
            
            <p>In attempting to make sense of the meaning of the Fourteenth Amendment, Thomas has pointed to the Civil Rights act of 1866 for guidance.<a href="#fn17" class="fn-ref">17</a> This act says that:</p>
            <blockquote>"[A]ll persons born in the United States <em>and not subject to any foreign power</em>&nbsp;.&nbsp;.&nbsp;.&nbsp;are hereby declared to be citizens of the United States."<a href="#fn18" class="fn-ref">18</a></blockquote>
                
            <p class="cont">The comparison finds a welcome home in Trump's overlap bewtweem alleigance, domicile, and citizenship. Thus, Thomas will likely gravitate to the Government’s original-public-meaning narrative: that “subject to the jurisdiction” incorporated the law-of-nations notion of allegiance and excluded children of those lacking the sovereign’s consent, paralleling his own reliance on the Law of Nations in cases like Gamble v. United States.<a href="#fn19" class="fn-ref">19</a> He may also be intrigued by the brief’s heavy use of ante-ratification treatises (Vattel, Story, Kent) and the claim that <em>Wong Kim Ark</em> was limited to domiciled aliens.<a href="#fn20" class="fn-ref">20</a> The States’ reliance on post-ratification practice and on OLC opinions, by contrast, is unlikely to carry much weight with him.</p>

            
            
            <br>
            <br>
            <h3 id="alito"><img src="https://www.supremecourt.gov/about/justice_pictures/Alito_9264-001-Crop.jpg" alt="Justice Samuel A. Alito, Jr." class="inline-icon">Justice Samuel A. Alito, Jr.</h3>
            <div class="scroll-anchor" id="alito-anchor"></div>
            <p>Alito’s opinions read like historical treatises. In McDonald, 561 U.S. 742, 758 78 (2010), he walked through centuries of gun rights history to show the Framers valued private arms. In immigration matters he views state frustration with illegal entry as constitutionally salient (Arizona v. United States, 567 U.S. 387, 416 35 (2012) (dissent)).</p>
            
            <p>When national policy tilts in ways the Founders never imagined, Alito pushes back. His Dobbs majority framed abortion rights as a 20th century innovation, 142 S. Ct. 2228, 2265 (2022). He will likely argue that automatic citizenship for children of unlawful entrants similarly lacks founding era pedigree. Supplementary citations—Kerry v. Din, 576 U.S. 86 (2015); NASA v. Nelson, 562 U.S. 134 (2011) (concurring); Kennedy v. Bremerton Sch. Dist., 142 S. Ct. 2407 (2022)—bolster his historic practice methodology and skepticism of unenumerated rights.</p>
            
            <p>Alito often tests historical arguments against practical consequences. The Government’s discussion of modern “birth tourism” and the incentive it creates for unlawful entry dovetails with his concerns in cases like Arizona v. United States and Hawaii v. Trump. (appellant) Yet Alito is also keen on stare decisis when a precedent is deeply rooted; the States’ portrayal of Wong Kim Ark as the cornerstone of 125 years of uniform practice—and their analogy to Afroyim v. Rusk’s repudiation of Dred Scott—gives him a counter-hook. (plaintiff)</p>


            
            <br>
            <br>
            <h3 id="sotomayor"><img src="https://www.supremecourt.gov/about/justice_pictures/Sotomayor_Official_2025.jpg" alt="Justice Sonia Sotomayor" class="inline-icon">Justice Sonia Sotomayor</h3>
            <div class="scroll-anchor" id="sotomayor-anchor"></div>
            <p>Sotomayor centers the lived experience of vulnerable groups. Her dissent in Trump v. Hawaii, 138 S. Ct. 2392, 2433 48 (2018), warned that the Court “fails to safeguard” America’s promise of religious neutrality. She joined the procedural win for Dreamers in DHS v. Regents, 140 S. Ct. 1891 (2020), and the equal citizenship decision in Morales Santana, 582 U.S. 47 (2017).</p>
            
            <p>Sotomayor’s willingness to foreground racial and social realities appears in Utah v. Strieff, 579 U.S. 232, 254 (2016) (dissent), and in oral arguments (United States v. Texas, 143 S. Ct. 1964 (2023)). She will treat the Order as creating a hereditary underclass—precisely what the Fourteenth Amendment repudiated.</p>
           
            <p>Expect Sotomayor to champion the States’ themes of equal dignity and the lived reality of children rendered stateless. Their brief highlights immediate harms to healthcare and foster-care programs and stresses the repudiation of Dred Scott. (plaintiff) She is also likely to cite the OLC opinions rejecting similar proposals and to emphasize the rule-of-law line from Plyler v. Doe to United States v. Texas that unlawful presence does not erase constitutional protections.</p>



            <br>
            <br>
            <h3 id="kagan"><img src="https://www.supremecourt.gov/about/justice_pictures/Kagan_10713-017-Crop.jpg" alt="Justice Elena Kagan" class="inline-icon">Justice Elena Kagan</h3>
            <div class="scroll-anchor" id="kagan-anchor"></div>
            <p>Kagan welds text, precedent, and workability. In Kisor v. Wilkie, 139 S. Ct. 2400, 2414 18 (2019), she salvaged Auer deference because “Congress has legislated against [it] for approaching a century.” She defends stare decisis as “a foundation stone of the rule of law” (Kimble v. Marvel, 576 U.S. 446, 455 56 (2015)).</p>
            
            <p>During Biden v. Nebraska argument (143 S. Ct. 2355 (2023)), she asked why the Secretary’s forgiveness plan was not simply carrying out congressional judgment—revealing concern for practical governance. Expect her to view reliance interests around birth right citizenship as overpowering any executive justification.</p>
           
            <p>Kagan will appreciate doctrinal coherence. The States’ argument that the Government’s position would upend not only Wong Kim Ark but also administrative and tax statutes that hinge on birthright citizenship will resonate with her structural pragmatism. (plaintiff) She may question the functionality of the Government’s allegiance test, probing hypo-theticals about dual citizens and long-term visa-holders.</p>



            <br>
            <br>
            <h3 id="gorsuch"><img src="https://www.supremecourt.gov/about/justice_pictures/Gorsuch2.jpg" alt="Justice Neil M. Gorsuch" class="inline-icon">Justice Neil M. Gorsuch</h3>
            <div class="scroll-anchor" id="gorsuch-anchor"></div>
            <p>For Gorsuch, words rule. In Bostock, 140 S. Ct. 1731, 1737 (2020), he wrote, “Only the written word is the law.” He has sided with immigrants when statutes demanded it (Sessions v. Dimaya, 138 S. Ct. 1204, 1223 (2018) (concurring); Niz Chavez v. Garland, 141 S. Ct. 1474, 1479 (2021)).</p>
            
            <p>The Citizenship Clause’s command—“All persons born…in the United States”—combined with his distrust of executive law making (Gundy v. United States, 139 S. Ct. 2116, 2131 35 (2019) (dissent)), positions him against the Order. His concurrence in NY State Rifle & Pistol Ass’n v. Bruen, 142 S. Ct. 2111, 2161 (2022), stresses that constitutional rights retain the scope they had “when the people adopted them,” reinforcing the textual argument.</p>
            
            <p>Gorsuch will respond to the Government’s natural-law framing that citizenship entails a reciprocal bond of allegiance and protection (he wrote similarly in Brackeen). (appellant) But he is equally protective of individual rights fixed at the Founding and Reconstruction. The States’ narrative that the Clause was adopted precisely to foreclose political manipulation of citizenship—linking the Order to a “modern Dred Scott” scenario—aligns with his textualist reliance on Reconstruction history in McGirt. (plaintiff)</p>



            <br>
            <br>
            <h3 id="kavanaugh"><img src="https://www.supremecourt.gov/about/justice_pictures/Kavanaugh%2012221_005_crop.jpg" alt="Justice Brett M. Kavanaugh" class="inline-icon">Justice Brett M. Kavanaugh</h3>
            <div class="scroll-anchor" id="kavanaugh-anchor"></div>
            <p>Kavanaugh evaluates precedent through a six factor test (Ramos v. Louisiana, 140 S. Ct. 1390, 1411 14 (2020) (concurring)). Here, reliance interests dwarf any seen in Ramos. His confirmation testimony calls precedent “critical” to Article III [Senate Jud. Comm. Hr’g Tr. 9 5 18].</p>
            
            <p>In DHS v. Regents, 140 S. Ct. 1891, 1933 (2020) (concurring in part, dissenting in part), he would have allowed DACA rescission but emphasized procedure and reliance. He seeks to limit collateral damage (Dobbs, 142 S. Ct. 2228, 2310 (2022) (concurring)) and voiced unease with dramatic constitutional shifts in Trump v. Anderson argument, 144 S. Ct. 662 (2024). The EO raises the very destabilization alarms he so often sounds.</p>
            
            <p>Kavanaugh often seeks a middle course grounded in precedent plus limiting principle. The Government gives him a limiting principle—children of parents here only temporarily or unlawfully—tied to historical practice under Elk v. Wilkins. (appellant) The States counter that any new carve-outs would spawn line-drawing chaos and administrative burden, themes that swayed him in the census-question litigation. (plaintiff) Which side better addresses administrability will matter.</p>



            <br>
            <br>
            <h3 id="barrett"><img src="https://www.supremecourt.gov/about/justice_pictures/Barrett_102535_w151.jpg" alt="Justice Amy Coney Barrett" class="inline-icon">Justice Amy Coney Barrett</h3>
            <div class="scroll-anchor" id="barrett-anchor"></div>
            <p>Barrett marries originalism with craft. In Fulton v. City of Philadelphia, 141 S. Ct. 1868, 1882 83 (2021) (concurring), she signaled openness to revisiting Employment Div. v. Smith yet refused to do so hastily. She probes temporal scope in historical analysis (see Bruen argument transcript, 2021).</p>
            
            <p>Barrett may distinguish Wong Kim Ark as covering only children of lawful residents, thereby upholding the EO without squarely overruling precedent—a familiar Barrett move. Her article “Originalism and Stare Decisis,” 92 Notre Dame L. Rev. 1921, 1925 28 (2017), foreshadows a balancing act between original meaning and precedent.</p>
            
            <p>Barrett’s writings stress historical semantics and the interaction of text with early practice. She will scrutinize the Government’s corpus of antebellum sources tying “jurisdiction” to allegiance and consent, but she also values Wong Kim Ark’s stare-decisis pedigree. The States’ detailed walk-through of the 39th Congress debates and their point that Senator Trumbull expressly affirmed birthright citizenship even for children of “Chinese and Gypsies” offers Barrett the sort of granular original-history she favors. (plaintiff)</p>



            <br>
            <br>
            <h3 id="jackson"><img src="https://www.supremecourt.gov/about/justice_pictures/KBJackson3.jpg" alt="Justice Ketanji Brown Jackson" class="inline-icon">Justice Ketanji Brown Jackson</h3>
            <div class="scroll-anchor" id="jackson-anchor"></div>
            <p>Jackson reads the Reconstruction Amendments through the lens of the injustices they were designed to remedy. Her SFFA v. Harvard dissent, 143 S. Ct. 2141, 2301 15 (2023), recounts how the Fourteenth Amendment sought to dismantle caste systems.</p>
            
            <p>On the district court, she curbed executive shortcuts (Make the Road N.Y. v. McAleenan, 405 F. Supp. 3d 1, 23, 59 (D.D.C. 2019); Ctr. for Biological Diversity v. McAleenan, 404 F. Supp. 3d 218, 240 (2019)). In Allen v. Milligan argument, she pressed Alabama on present day racial dynamics. She will likely write separately to underscore how the EO resurrects the caste distinctions the Citizenship Clause abolished after Dred Scott.</p>
           
            <p>Jackson focuses on text, purpose, and contemporary impact. She is apt to seize on the States’ integration of the Fourteenth Amendment’s purpose—to constitutionalize the Civil Rights Act of 1866—and their demonstration that Congress knew the Clause covered children of non-citizens. (plaintiff)The Government’s reliance on 19th-century treatises will get respectful scrutiny, but the States’ statutory-text-plus-precedent approach fits her methodology seen in Biden v. Nebraska concurrence.</p>



            <br>
            <br>
            <p style="margin-bottom: 60px;"></p>

            <h3 id="conclusion" class="conclusion"><ul>CONCLUSION</ul></h3>
            <div class="scroll-anchor" id="conclusion-anchor"></div>
            <p>Digital transformation has fundamentally altered the landscape of academic research, creating new possibilities while challenging established practices<a href="#fn" class="fn-ref">13</a>. The successful navigation of this transition requires thoughtful adaptation, continued investment in digital infrastructure, and a commitment to preserving the core values of scholarly inquiry.</p>

            <p>As we move forward, the academic community must work collectively to ensure that digital tools serve to democratize knowledge creation while maintaining the rigorous standards that define quality research<a href="#fn" class="fn-ref">14</a>.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<a href="#fn" class="fn-ref">15</a> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<a href="#fn" class="fn-ref">16</a> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.<a href="#fn" class="fn-ref">17</a> Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.</p>
        </div>

        <!-- Footnotes -->
        <div class="footnotes" id="footnotes">
            <h3>Notes</h3>
            
            <div class="footnote" id="fn1" data-ref="1">
                <span class="footnote-number">1.</span>
                <span style="font-variant: small-caps;">U.S. Const.</span>, Amend. XIV, § 1, cl.&nbsp;1.
            </div>

            <div class="footnote" id="fn2" data-ref="2">
                <span class="footnote-number">2.</span>
                Executive Order No. 14160, "Protecting the Meaning and Value of American Citizenship", 90 FR 8449 (Jan. 20 2025).
            </div>

            <div class="footnote" id="fn3" data-ref="3">
                <span class="footnote-number">3.</span>
                Order Granting Temporary Restraining Order, <em>Washington v. Trump</em>, No. C25-0127-JCC, 765 F. Supp. 3d 1142 (W.D. Wash. Jan. 23, 2025); Order Granting Prelimenary Injunction, <em>Washington v. Trump</em>, No. C25-0127-JCC (W.D. Wash. Feb. 6, 2025).
            </div>

            <div class="footnote" id="fn4" data-ref="4">
                <span class="footnote-number">4.</span>
                Order Deferring Application for Stay, <em>Washington v. Trump</em>, No. C25-0127-JCC (W.D. Apr. 21, 2025).
            </div>

            <div class="footnote" id="fn5" data-ref="5">
                <span class="footnote-number">5.</span>
                169 U.S. 649 (1898).
            </div>

            <div class="footnote" id="fn6" data-ref="6">
                <span class="footnote-number">6.</span>
                <em>NFIB v. Sebelius</em>, 567 U.S. 519, 538 (2012).
            </div>

            <div class="footnote" id="fn7" data-ref="7">
                <span class="footnote-number">7.</span>
                <em>Dep’t of Commerce v. New York</em>, 139 S. Ct. 2551, 2575 76 (2019).
            </div>

            <div class="footnote" id="fn8" data-ref="8">
                <span class="footnote-number">8.</span>
                <em>See June Medical Servs. v. Russo</em>, 140 S. Ct. 2103, 2134 (2020) (Roberts, J., concurring) (stare decisis requires “treat[ing] like cases alike”).
            </div>

            <div class="footnote" id="fn9" data-ref="9">
                <span class="footnote-number">9.</span>
                <em>See, e.g.</em>, <em>Sessions v. Morales Santana</em>, 582 U.S. 47, 52 53 (2017).
            </div>

            <div class="footnote" id="fn10" data-ref="10">
                <span class="footnote-number">10.</span>
                <em>Dobbs v. Jackson Women's Health Organization</em>, 142 S. Ct. 2228, 2316 (2022).
            </div>

            <div class="footnote" id="fn11" data-ref="11" style="font-style: normal;">
                <span class="footnote-number">11.</span>
                Plaintiff States' Answering Brief at 17, <em>Washington v. Trump</em>, No. 25-807 at (9th Cir. Apr. 4, 2025) [hereinafter States' Brief].
            </div>

            <div class="footnote" id="fn12" data-ref="12" style="font-style: normal;">
                <span class="footnote-number">12.</span>
                <em>Cf.</em> Transcript of Oral Argument at 75, <em>Murthy v. Missouri</em>, 603 U.S. 43 (2024) (expressing concerns about a judicial patchwork of scrutiny towards expressive coercion). <em>See Gill v. Whitford</em>, 585 U.S. 48, 50 (2018) (same for concerns about a fix for gerrymandering that jumps the shark).
            </div>

            <div class="footnote" id="fn13" data-ref="13">
                <span class="footnote-number">13.</span>
                Appellants Brief at 15, <em>Washington v. Trump</em>, No. 25-807 (9th Cir. Mar. 7, 2025) [hereinafter Trump's Brief].
            </div>

            <div class="footnote" id="fn14" data-ref="14">
                <span class="footnote-number">14.</span>
                <em>Biden v. Nebraska</em>, 600 U.S. 477, 506 (2023) (Roberts, J., Majority Opinion).
            </div>

            <div class="footnote" id="fn15" data-ref="15">
                <span class="footnote-number">15.</span>
                <em>Saenz v. Roe</em>, 526 U.S. 489, 521–28 (1999) (dissenting) (urging a revitilization of the Privileges or Immunities&nbsp;Clause as applied to welfare benefits); <em>McDonald v. Chicago</em>, 561 U.S. 742, 805–13 (2010) (concurring) (same as applied to 2nd Amendment protections).
            </div>

            <div class="footnote" id="fn16" data-ref="16">
                <span class="footnote-number">16.</span>
                <em>Gamble v. United States</em>, 139 S. Ct. 1960, 1981–84 (2019) (concurring).
            </div>

            <div class="footnote" id="fn17" data-ref="17">
                <span class="footnote-number">17.</span>
                <em>See U.S. v. Vaello Madero</em>, 142 S. Ct. 1539, 1548 (2022) (concurring).
            </div>

            <div class="footnote" id="fn18" data-ref="18">
                <span class="footnote-number">18.</span>
                Civil Rights Act of 1866, ch. 31, § 1, 14 Stat. 27, 27 (emphasis added).
            </div>
            
            <div class="footnote" id="fn19" data-ref="19">
                <span class="footnote-number">19.</span>
                U.S. v. Gamble,
            </div>

            <div class="footnote" id="fn20" data-ref="20">
                <span class="footnote-number">20.</span>
                Trump's Brief at 21–4.
            </div>
            <div class="footnote" id="fn" data-ref="">
                <span class="footnote-number">21.</span>
                
            </div>
            <div class="footnote" id="fn" data-ref="">
                <span class="footnote-number">22.</span>
                
            </div>
            <div class="footnote" id="fn" data-ref="">
                <span class="footnote-number">23.</span>
                
            </div>
            <div class="footnote" id="fn" data-ref="">
                <span class="footnote-number">24.</span>
                
            </div>
            <div class="footnote" id="fn" data-ref="">
                <span class="footnote-number">25.</span>
                
            </div>

            
        </div>
    </div>

    <script>
        // Table of Contents functionality
        document.addEventListener('DOMContentLoaded', function() {
            const tocItems = document.querySelectorAll('.toc-item');
            const tocToggles = document.querySelectorAll('.toc-toggle');
            const mainContent = document.getElementById('main-content');
            const footnotes = document.querySelector('.footnotes');
            
            
            let isScrollingSynced = false;

            // TOC navigation
            tocItems.forEach(item => {
                item.addEventListener('click', function(e) {
                    e.stopPropagation();
                    const target = this.getAttribute('data-target');
                    if (target) {
                        const element = document.getElementById(target);
                        const realElement = document.getElementById(target.slice(0, -7)); // Remove '-anchor' suffix
                        if (element) {
                            mainContent.scrollTo({ top: element.offsetTop - realElement.offsetHeight - 5, behavior: 'smooth' }); // Scroll to the section, accounting for the header height
                            
                            // Update active state
                            tocItems.forEach(i => i.classList.remove('active'));
                            this.classList.add('active');
                        }
                    }
                });
            });

            // scroll-to-top on TOC title click
            const tocTitle = document.querySelector('#floating-header h1');
            if (tocTitle) {
                 tocTitle.addEventListener('click', () => {
                 mainContent.scrollTo({ top: 0, behavior: 'smooth' });
                });
            }   

            // TOC collapsible sections
            tocToggles.forEach(toggle => {
                toggle.addEventListener('click', function(e) {
                    e.stopPropagation();
                    const nested = this.parentElement.nextElementSibling;
                    if (nested && nested.classList.contains('toc-nested')) {
                        nested.classList.toggle('collapsed');
                        this.textContent = nested.classList.contains('collapsed') ? '▶' : '▼';
                    }
                });
            });

            // Synchronized scrolling between main content and footnotes (1:1 pixel sync)
function syncFootnotesScroll() {
    if (isScrollingSynced) return;
    
    const mainScrollTop = mainContent.scrollTop;
    
    isScrollingSynced = true;
    footnotes.scrollTop = mainScrollTop;
    
    requestAnimationFrame(() => {
        isScrollingSynced = false;
    });
}

function syncMainContentScroll() {
    if (isScrollingSynced) return;
    
    const footnotesScrollTop = footnotes.scrollTop;
    
    isScrollingSynced = true;
    mainContent.scrollTop = footnotesScrollTop;
    
    requestAnimationFrame(() => {
        isScrollingSynced = false;
    });
}

            // Add scroll event listeners for synchronization
            mainContent.addEventListener('scroll', syncFootnotesScroll);
            footnotes.addEventListener('scroll', syncMainContentScroll);

            // Initialize footnotes - detect which ones need truncation
            function initializeFootnotes() {
                const footnotes = document.querySelectorAll('.footnote');
                footnotes.forEach(footnote => {
                    // Create a temporary element to measure text height
                    const tempDiv = document.createElement('div');
                    tempDiv.style.cssText = `
                        position: absolute;
                        visibility: hidden;
                        width: ${footnote.offsetWidth - 20}px;
                        font-size: 13px;
                        line-height: 1.5;
                        padding: 10px;
                    `;
                    tempDiv.innerHTML = footnote.innerHTML;
                    document.body.appendChild(tempDiv);
                    
                    const maxHeight = 1.5 * 13 * 5 + 20; // 5 lines + padding
                    
                    // Only convert to extended-footnote if it actually exceeds the height limit
                    if (tempDiv.offsetHeight > maxHeight) {
                        footnote.className = footnote.className.replace('footnote', 'extended-footnote');
                    }
                    // If it doesn't exceed the limit, leave it as regular footnote (no ellipses)
                    
                    document.body.removeChild(tempDiv);
                });
            }

            // Footnote reference highlighting and expansion
            const footnoteRefs = document.querySelectorAll('.fn-ref');
            footnoteRefs.forEach(ref => {
                ref.addEventListener('mouseenter', function() {
                    const refNumber = this.getAttribute('href').substring(3);
                    const footnote = document.getElementById('fn' + refNumber);
                    if (footnote) {
                        footnote.classList.add('highlighted');
                        if (footnote.classList.contains('extended-footnote')) {
                            footnote.classList.add('expanded');
                        }
                    }
                });

                ref.addEventListener('mouseleave', function() {
                    const refNumber = this.getAttribute('href').substring(3);
                    const footnote = document.getElementById('fn' + refNumber);
                    if (footnote) {
                        footnote.classList.remove('highlighted');
                        footnote.classList.remove('expanded');
                    }
                });

                // Click to jump to footnote
                ref.addEventListener('click', function(e) {
                    e.preventDefault();
                    const refNumber = this.getAttribute('href').substring(3);
                    const footnote = document.getElementById('fn' + refNumber);
                    if (footnote) {
                        footnote.scrollIntoView({ behavior: 'smooth', block: 'center' });
                        footnote.classList.add('highlighted');
                        if (footnote.classList.contains('extended-footnote')) {
                            footnote.classList.add('expanded');
                        }
                        setTimeout(() => {
                            footnote.classList.remove('highlighted');
                            footnote.classList.remove('expanded');
                        }, 2000);
                    }
                });
            });

            

            // Direct footnote hover for both types
            const allFootnotes = document.querySelectorAll('.footnote, .extended-footnote');
            allFootnotes.forEach(footnote => {
                footnote.addEventListener('mouseenter', function() {
                    this.classList.add('highlighted');
                    if (this.classList.contains('extended-footnote')) {
                        this.classList.add('expanded');
                    }
                    
                    // Highlight corresponding footnote reference in middle column
                    const refNumber = this.getAttribute('data-ref');
                    const footnoteRef = document.querySelector(`a[href="#fn${refNumber}"]`);
                    if (footnoteRef) {
                        footnoteRef.style.backgroundColor = '#3498db';
                        footnoteRef.style.color = 'white';
                    }
                });

                footnote.addEventListener('mouseleave', function() {
                    this.classList.remove('highlighted');
                    this.classList.remove('expanded');
                    
                    // Remove highlight from footnote reference
                    const refNumber = this.getAttribute('data-ref');
                    const footnoteRef = document.querySelector(`a[href="#fn${refNumber}"]`);
                    if (footnoteRef) {
                        footnoteRef.style.backgroundColor = '';
                        footnoteRef.style.color = '';
                    }
                });

                footnote.addEventListener('click', function(e) {
        const refNumber = this.getAttribute('data-ref');
        const footnoteRef = document.querySelector(`a[href="#fn${refNumber}"]`);
        
        if (footnoteRef) {
            // Scroll the main content to bring the reference into view
            footnoteRef.scrollIntoView({ behavior: 'smooth', block: 'center' });
            
            // Highlight the reference
            footnoteRef.style.backgroundColor = '#3498db';
            footnoteRef.style.color = 'white';
            
            // Remove highlight after 2 seconds
            setTimeout(() => {
                footnoteRef.style.backgroundColor = '';
                footnoteRef.style.color = '';
            }, 2000);
        }
    });
            });

            // Simple footnote positioning - run once at startup
            function smartPositionFootnotes() {
                const footnoteRefs = document.querySelectorAll('.fn-ref');
                const footnotesContainer = document.querySelector('.footnotes');
                const mainContent = document.getElementById('main-content');
                
                if (!mainContent || !footnotesContainer || footnoteRefs.length === 0) return;
                
                const minDistance = 10;
                const headerHeight = 20;
                let previousFootnoteBottom = headerHeight;
                
                footnoteRefs.forEach(ref => {
                    const refNumber = ref.getAttribute('href').substring(3);
                    const footnote = document.getElementById('fn' + refNumber);
                    
                    if (!footnote) return;
                    
                    // Reset any existing transform
                    footnote.style.transform = '';
                    
                    // Use offsetTop for position calculation (relative to content container)
                    // This is unaffected by sticky headers
                    const refOffsetTop = ref.offsetTop;
                    const idealTop = refOffsetTop + headerHeight;
                    const safeTop = Math.max(headerHeight + 20, idealTop);
                    
                    let finalTop;
                    if (safeTop >= previousFootnoteBottom + minDistance) {
                        finalTop = safeTop;
                    } else {
                        finalTop = previousFootnoteBottom + minDistance;
                    }
                    
                    const currentTop = footnote.offsetTop;
                    const translateY = finalTop - currentTop;
                    
                    if (!footnote.style.top) {
                        footnote.style.top = '0px';
                        footnote.style.position = 'relative';
                        footnote.style.transition = 'top 0.5s ease, transform 0.3s ease, box-shadow 0.3s ease, opacity 0.3s ease';
                        footnote.offsetHeight;
                    }
                    
                    footnote.style.top = `${translateY}px`;
                    
                    previousFootnoteBottom = finalTop + footnote.offsetHeight;
                });
            }

            

            // Active section detection and TOC auto-expansion
            function updateActiveSection() {
                const sections = document.querySelectorAll('h2[id], h3[id]');
                let currentSection = null;
                
                sections.forEach(section => {
                    const rect = section.getBoundingClientRect();
                    const contentRect = mainContent.getBoundingClientRect();
                    if (rect.top >= contentRect.top && rect.top <= contentRect.top + 150) {
                        currentSection = section.id;
                    }
                });
                
                if (currentSection) {
                    tocItems.forEach(item => {
                        item.classList.remove('active');
                        const target = item.getAttribute('data-target');
                        if (target.slice(0, -7) === currentSection) {
                            item.classList.add('active');
                            
                            // Check if this item is in a collapsed section and expand it
                            let parentElement = item.parentElement;
                            if (parentElement && parentElement.classList.contains('toc-nested') && parentElement.classList.contains('collapsed')) {
                                parentElement.classList.remove('collapsed');
                                const prevSibling = parentElement.previousElementSibling;
                                if (prevSibling && prevSibling.querySelector('.toc-toggle')) {
                                    prevSibling.querySelector('.toc-toggle').textContent = '▼';
                                }
                            }
                        }
                    });
                }
            }

            

            // Floating header animation
            function updateFloatingHeader() {
                const mainTitle = document.querySelector('.content h1');
                const mainSubtitle = document.querySelector('.content .subtitle');
                const floatingHeader = document.getElementById('floating-header');
                const tocHeading = document.querySelector('.toc h3');
                const tocItemsContainer = document.getElementById('toc-items-container');
                
                if (mainTitle && floatingHeader && tocHeading && tocItemsContainer) {
                    const titleRect = mainTitle.getBoundingClientRect();
                    const subtitleRect = mainSubtitle ? mainSubtitle.getBoundingClientRect() : titleRect;
                    const contentRect = mainContent.getBoundingClientRect();
                    
                    // Show floating header when main title and subtitle are scrolled out of view
                    if (subtitleRect.bottom < contentRect.top + 50) {
                        floatingHeader.classList.add('visible');
                        tocHeading.classList.add('hidden');
                        tocItemsContainer.classList.add('shifted');
                    } else {
                        floatingHeader.classList.remove('visible');
                        tocHeading.classList.remove('hidden');
                        tocItemsContainer.classList.remove('shifted');
                    }
                }
            }

            function updateStickyHeadings() {
                const h3Elements = document.querySelectorAll('.content h3');
                const contentRect = mainContent.getBoundingClientRect();
                
                h3Elements.forEach(h3 => {
                    const rect = h3.getBoundingClientRect();
                    // Check if the h3 is stuck at the top (within a few pixels of the content top)
                    if (rect.top <= contentRect.top + 5 && rect.bottom > contentRect.top) {
                        h3.classList.add('is-stuck');
                    } else {
                        h3.classList.remove('is-stuck');
                    }
                });
            }


            /**
             * Ensures the footnotes column can scroll the full height of the main content
             * by appending a spacer div whose height equals the difference.
             */
            function addFootnotesSpacer() {
            const main    = document.getElementById('main-content');
            const foot    = document.querySelector('.footnotes');
            if (!main || !foot) return;

            // Measure total scrollable heights
            const mainHeight = main.scrollHeight;
            const footHeight = foot.scrollHeight;
            const diff       = mainHeight - footHeight;

            // Remove any existing spacer
            const existing = foot.querySelector('.footnotes-spacer');
            if (existing) {
                foot.removeChild(existing);
            }

            // Only add spacer if main is taller
            if (diff > 0) {
                const spacer = document.createElement('div');
                spacer.className = 'footnotes-spacer';
                spacer.style.height = diff + 'px';
                spacer.style.width  = '1px';         // minimal width
                spacer.style.pointerEvents = 'none'; // non-interactive
                foot.appendChild(spacer);
            }
            }

           

            // Initialize footnotes on page load
            initializeFootnotes();

            // Main scroll event handler
            mainContent.addEventListener('scroll', function() {
                updateActiveSection();
                updateFloatingHeader();
                updateStickyHeadings();
            });
            
            updateActiveSection(); // Initial call
            updateFloatingHeader(); // Initial call
            updateStickyHeadings(); // Initial call
            
            // Initial smart positioning after everything loads
            setTimeout(() => {
                smartPositionFootnotes();
                addFootnotesSpacer();
            }, 300);
            
         window.addEventListener('resize', addFootnotesSpacer);
        });
    </script>
</body>
</html>
