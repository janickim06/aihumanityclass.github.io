+++
date = "13 Jan 2026"
draft = false
title = "Schedule"
slug = "schedule"
+++


# Table Team Schedule

<style>
  table {
    width: 100%;
    border-collapse: collapse;
    font-family: sans-serif;
  }
  /* UPDATED: Changed text-align to center */
        td {
            padding: 5px;
            text-align: center; 
            border-bottom: 1px solid #ddd;
        }

  th {
    text-align: center;
    background-color: #f2f2f2;
    font-weight: bold;
  }
  tr:nth-child(even) {
    background-color: #f9f9f9;
  }
  .center-text {
    text-align: center !important; /* !important ensures it overrides other rules */
  }

  /* --- SNOW DAY ROW STYLES --- */
        .snow-day-row {
            background: linear-gradient(135deg, #e0f7fa 0%, #b3e5fc 100%);
            color: #0277bd;
            position: relative;
            overflow: hidden;
            border-left: 5px solid #0288d1;
        }

        .snow-day-row td {
            /* padding: 20px 15px; */
            font-weight: bold;
            position: relative;
            z-index: 2; /* Keep text above snowflakes */
        }

        /* Date Column Styling */
        .snow-date {
            display: flex;
            align-items: center;
        }

        /* Message Column Styling */
        .snow-message {
            letter-spacing: 1px;
            color: #01579b;
        }

        /* Animated Snowflake Decoration */
        .snowflake {
            position: absolute;
            top: -10px;
            color: rgba(255, 255, 255, 0.8);
            font-size: 1.5em;
            animation: fall linear infinite;
            z-index: 1;
            pointer-events: none;
        }

        /* Snowflake Animation Keyframes */
        @keyframes fall {
            0% { transform: translateY(-20px) rotate(0deg); opacity: 0; }
            20% { opacity: 1; }
            100% { transform: translateY(80px) rotate(360deg); opacity: 0; }
        }

        /* Specific positioning for flakes */
        .flake-1 { left: 10%; animation-duration: 3s; animation-delay: 0s; font-size: 1.2rem; }
        .flake-2 { left: 30%; animation-duration: 4s; animation-delay: 1s; font-size: 1.8rem; }
        .flake-3 { left: 60%; animation-duration: 2.5s; animation-delay: 0.5s; font-size: 1rem; }
        .flake-4 { left: 85%; animation-duration: 3.5s; animation-delay: 2s; font-size: 1.5rem; }

        /* Responsive adjustments */
        @media (max-width: 480px) {
            .snow-day-row td {
                display: block;
                width: 100%;
                text-align: center;
            }
            .snow-date {
                justify-content: center;
            }
        }
</style>

<table>
  <thead>
    <tr>
      <th class="center-text">Date</th>
      <th class="center-text">News Team</th>
      <th class="center-text">Lead Team</th>
      <th class="center-text">Blog Team</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Tuesday 20 Jan</td>
      <td>1</td>
      <td>5</td>
      <td>9</td>
    </tr>
    <tr>
      <td>Thursday 22 Jan</td>
      <td>2</td>
      <td>6</td>
      <td>10</td>
    </tr>
    <tr class="snow-day-row">
    <td>
      <div class="snowflake flake-1">❄️</div>
      <div class="snowflake flake-2">❅</div>
      <div class="snowflake flake-3">❆</div>
      <div class="snowflake flake-4">❄️</div>
      <span>Tuesday 27 Jan</span>
    </td>
    <td colspan="3" class="snow-message">☃️ Snow Day! ❄️</td>
  </tr>
    <tr>
      <td>Thursday 29 Jan</td>
      <td>3</td>
      <td>7</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Tuesday 3 Feb</td>
      <td>4</td>
      <td>8</td>
      <td>12</td>
    </tr>
    <tr>
      <td>Thursday 5 Feb</td>
      <td>5</td>
      <td>9</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Tuesday 10 Feb</td>
      <td>6</td>
      <td>10</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Thursday 12 Feb</td>
      <td>7</td>
      <td>11</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Tuesday 17 Feb</td>
      <td>8</td>
      <td>12</td>
      <td>4</td>
    </tr>
    <tr>
      <td>Thursday 19 Feb</td>
      <td>9</td>
      <td>1</td>
      <td>5</td>
    </tr>
    <tr>
      <td>Tuesday 24 Feb</td>
      <td>10</td>
      <td>2</td>
      <td>6</td>
    </tr>
    <tr>
      <td>Thursday 26 Feb</td>
      <td>11</td>
      <td>3</td>
      <td>7</td>
    </tr>
    <tr style="background-color: #d1fae5;">
      <td></td>
            <td colspan=3 class="center-text">Spring Break</td>
    </tr>
    <tr>
      <td>Tuesday 10 Mar</td>
      <td>12</td>
      <td>4</td>
      <td>8</td>
    </tr>
    <tr>
      <td>Thursday 12 Mar</td>
      <td>1</td>
      <td>5</td>
      <td>9</td>
    </tr>
    <tr>
      <td>Tuesday 17 Mar</td>
      <td>2</td>
      <td>6</td>
      <td>10</td>
    </tr>
    <tr>
      <td>Thursday 19 Mar</td>
      <td>3</td>
      <td>7</td>
      <td>11</td>
    </tr>
    <tr>
      <td>Tuesday 24 Mar</td>
      <td>4</td>
      <td>8</td>
      <td>12</td>
    </tr>
    <tr>
      <td>Thursday 26 Mar</td>
      <td>5</td>
      <td>9</td>
      <td>1</td>
    </tr>
    <tr>
      <td>Tuesday 31 Mar</td>
            <td colspan=3 class="center-text">Review and Recap</td>
    </tr>
    <tr>
      <td>Thursday 2 Apr</td>
            <td colspan=3 class="center-text">Midterm</td>
    </tr>
    <tr>
      <td>Tuesday 7 Apr</td>
      <td>6</td>
      <td>10</td>
      <td>2</td>
    </tr>
    <tr>
      <td>Thursday 9 Apr</td>
      <td>7</td>
      <td>11</td>
      <td>3</td>
    </tr>
    <tr>
      <td>Tuesday 14 Apr</td>
      <td>8</td>
      <td>12</td>
      <td>4</td>
    </tr>
    <tr style="background-color: #faf3d1ff;">
      <td>Thursday 16 Apr</td>
      <td colspan=3 class="center-text">Project Draft Presentations</td>
    </tr>
    <tr style="background-color: #effad1ff;">
      <td>Tuesday 21 Apr</td>
      <td colspan=3 class="center-text">Project Draft Presentations</td>
    </tr>
    <tr style="background-color: #faf3d1ff;">
      <td>Thursday 23 Apr</td>
      <td colspan=3 class="center-text">Project Draft Presentations</td>
    </tr>
    <tr style="background-color: #effad1ff;">
      <td>Tuesday 28 Apr</td>
      <td colspan=3 class="center-text">Project Draft Presentations</td>
    </tr>
  </tbody>
</table>
