<!DOCTYPE html>                                                                                                                                                                                  
  <html lang="en">                                          
  <head>                                                                                                                                                                                           
    <meta charset="UTF-8" />                                
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Terms of Service – SenC</title>                                                                                                                                                         
    <style>
      * { margin: 0; padding: 0; box-sizing: border-box; }                                                                                                                                         
                                                                                                                                                                                                   
      body {
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;                                                                                                            
        background: #0f0f0f;                                
        color: #e0e0e0;                                                                                                                                                                            
        line-height: 1.7;
      }                                                                                                                                                                                            
                                                            
      header {
        background: #1a1a1a;
        border-bottom: 1px solid #2a2a2a;                                                                                                                                                          
        padding: 20px 0;
        text-align: center;                                                                                                                                                                        
      }                                                     

      header .logo {                                                                                                                                                                               
        font-size: 24px;
        font-weight: 700;                                                                                                                                                                          
        color: #ffffff;                                     
        letter-spacing: -0.5px;
      }
                                                                                                                                                                                                   
      header .logo span {
        background: linear-gradient(135deg, #a855f7, #ec4899);                                                                                                                                     
        -webkit-background-clip: text;                      
        -webkit-text-fill-color: transparent;                                                                                                                                                      
      }
                                                                                                                                                                                                   
      .hero {                                               
        background: linear-gradient(135deg, #1a0a2e 0%, #16082a 50%, #0f0f0f 100%);
        padding: 60px 24px 50px;                                                                                                                                                                   
        text-align: center;                                                                                                                                                                        
        border-bottom: 1px solid #2a2a2a;                                                                                                                                                          
      }                                                                                                                                                                                            
                                                            
      .hero h1 {                                                                                                                                                                                   
        font-size: 32px;
        font-weight: 700;                                                                                                                                                                          
        color: #ffffff;                                     
        margin-bottom: 12px;
      }

      .hero .meta {                                                                                                                                                                                
        font-size: 14px;
        color: #888;                                                                                                                                                                               
      }                                                     

      .hero .meta strong {
        color: #aaa;
      }                                                                                                                                                                                            
   
      .container {                                                                                                                                                                                 
        max-width: 760px;                                   
        margin: 0 auto;
        padding: 48px 24px 80px;
      }                                                                                                                                                                                            
   
      .section {                                                                                                                                                                                   
        background: #1a1a1a;                                
        border: 1px solid #2a2a2a;
        border-radius: 16px;
        padding: 28px 32px;                                                                                                                                                                        
        margin-bottom: 20px;
      }                                                                                                                                                                                            
                                                            
      .section-number {                                                                                                                                                                            
        display: inline-block;
        background: linear-gradient(135deg, #a855f7, #ec4899);                                                                                                                                     
        color: #fff;                                        
        font-size: 11px;
        font-weight: 700;                                                                                                                                                                          
        padding: 3px 10px;
        border-radius: 20px;                                                                                                                                                                       
        margin-bottom: 12px;                                
        letter-spacing: 0.5px;
        text-transform: uppercase;                                                                                                                                                                 
      }
                                                                                                                                                                                                   
      .section h2 {                                         
        font-size: 18px;
        font-weight: 700;
        color: #ffffff;                                                                                                                                                                            
        margin-bottom: 14px;
      }                                                                                                                                                                                            
                                                            
      .section p {
        font-size: 15px;
        color: #c0c0c0;
        margin-bottom: 12px;                                                                                                                                                                       
      }
                                                                                                                                                                                                   
      .section p:last-child { margin-bottom: 0; }           

      .section ul {
        list-style: none;
        margin-top: 8px;                                                                                                                                                                           
      }
                                                                                                                                                                                                   
      .section ul li {                                      
        font-size: 15px;
        color: #c0c0c0;                                                                                                                                                                            
        padding: 8px 0 8px 20px;
        border-bottom: 1px solid #252525;                                                                                                                                                          
        position: relative;                                                                                                                                                                        
      }
                                                                                                                                                                                                   
      .section ul li:last-child { border-bottom: none; }    

      .section ul li::before {
        content: '✕';
        position: absolute;                                                                                                                                                                        
        left: 0;
        color: #ec4899;                                                                                                                                                                            
        font-size: 11px;                                    
        top: 10px;
      }                                                                                                                                                                                            
   
      .section ul li strong { color: #ffffff; }                                                                                                                                                    
                                                            
      .highlight-box {                                                                                                                                                                             
        background: #12082a;
        border: 1px solid #6d28d9;                                                                                                                                                                 
        border-radius: 12px;                                
        padding: 20px 24px;
        margin: 16px 0;                                                                                                                                                                            
      }
                                                                                                                                                                                                   
      .highlight-box .price {                               
        font-size: 28px;
        font-weight: 800;                                                                                                                                                                          
        color: #ffffff;
      }                                                                                                                                                                                            
                                                            
      .highlight-box .price span {
        font-size: 15px;
        font-weight: 400;
        color: #888;                                                                                                                                                                               
      }
                                                                                                                                                                                                   
      .highlight-box .plan-name {                           
        font-size: 13px;
        color: #a855f7;
        font-weight: 600;                                                                                                                                                                          
        margin-bottom: 4px;
        text-transform: uppercase;                                                                                                                                                                 
        letter-spacing: 1px;                                
      }                                                                                                                                                                                            
   
      .steps {                                                                                                                                                                                     
        margin-top: 16px;                                   
      }

      .step {
        display: flex;
        align-items: flex-start;
        gap: 14px;                                                                                                                                                                                 
        padding: 12px 0;
        border-bottom: 1px solid #252525;                                                                                                                                                          
      }                                                     

      .step:last-child { border-bottom: none; }                                                                                                                                                    
   
      .step-icon {                                                                                                                                                                                 
        width: 32px;                                        
        height: 32px;
        border-radius: 8px;
        display: flex;
        align-items: center;
        justify-content: center;                                                                                                                                                                   
        font-size: 16px;
        flex-shrink: 0;                                                                                                                                                                            
        margin-top: 2px;                                    
      }

      .step-icon.ios { background: #1a1a2e; }                                                                                                                                                      
      .step-icon.android { background: #0d2318; }
                                                                                                                                                                                                   
      .step-content strong {                                
        display: block;                                                                                                                                                                            
        font-size: 13px;                                    
        color: #fff;
        margin-bottom: 4px;
      }                                                                                                                                                                                            
   
      .step-content p {                                                                                                                                                                            
        font-size: 13px;                                    
        color: #888;
        margin: 0;
      }

      .step-content code {                                                                                                                                                                         
        background: #252525;
        padding: 2px 6px;                                                                                                                                                                          
        border-radius: 4px;                                 
        font-family: monospace;
        font-size: 12px;
        color: #ccc;                                                                                                                                                                               
      }
                                                                                                                                                                                                   
      .warning-box {                                        
        background: #1a0a0a;
        border: 1px solid #7f1d1d;
        border-radius: 10px;                                                                                                                                                                       
        padding: 14px 18px;
        margin-top: 16px;                                                                                                                                                                          
        font-size: 14px;                                    
        color: #fca5a5;                                                                                                                                                                            
      }
                                                                                                                                                                                                   
      .warning-box strong { color: #f87171; }               

      footer {
        background: #1a1a1a;
        border-top: 1px solid #2a2a2a;                                                                                                                                                             
        padding: 32px 24px;
        text-align: center;                                                                                                                                                                        
      }                                                     

      footer p {
        font-size: 13px;
        color: #555;                                                                                                                                                                               
        margin-bottom: 8px;
      }                                                                                                                                                                                            
                                                            
      footer a {
        color: #a855f7;
        text-decoration: none;
      }

      footer a:hover { text-decoration: underline; }                                                                                                                                               
   
      @media (max-width: 600px) {                                                                                                                                                                  
        .hero h1 { font-size: 24px; }                       
        .section { padding: 20px 18px; }
        .highlight-box { padding: 16px 18px; }                                                                                                                                                     
      }
    </style>                                                                                                                                                                                       
  </head>                                                                                                                                                                                          
  <body>
                                                                                                                                                                                                   
  <header>                                                  
    <div class="logo"><span>SenC</span></div>
  </header>

  <div class="hero">
    <h1>Terms of Service</h1>
    <p class="meta">                                                                                                                                                                               
      <strong>Last Updated:</strong> April 11, 2026 &nbsp;·&nbsp;
      <strong>Provider:</strong> Aquaguard Teknoloji Bilgisayar Ltd. Şti. (Turkey) &nbsp;·&nbsp;                                                                                                   
      <strong>Contact:</strong> support@aquaguardwd.com                                                                                                                                            
    </p>                                                                                                                                                                                           
  </div>                                                                                                                                                                                           
                                                                                                                                                                                                   
  <div class="container">                                   

    <div class="section">
      <span class="section-number">Section 1</span>
      <h2>Acceptance of Terms and Age Limit</h2>
      <p>By using <strong>SenC</strong>, you agree to these terms. To use the App, you must be at least 13 years old (16 in the EU). Paid subscriptions require you to be 18 or have parental      
  consent.</p>                                                                                                                                                                                     
    </div>                                                                                                                                                                                         
                                                                                                                                                                                                   
    <div class="section">                                   
      <span class="section-number">Section 2</span>
      <h2>User-Generated Content &amp; Zero Tolerance Policy</h2>                                                                                                                                  
      <p>Sharing the following content is <strong>strictly prohibited</strong> and will result in an immediate ban without warning:</p>
      <ul>                                                                                                                                                                                         
        <li><strong>Nudity and Pornography:</strong> Any sexual content or extreme nudity.</li>
        <li><strong>Child Sexual Abuse Material (CSAM):</strong> Anything endangering minors — reported to law enforcement immediately.</li>                                                       
        <li><strong>Violence and Gore:</strong> Human or animal abuse, shocking violence.</li>                                                                                                     
        <li><strong>Hate Speech and Harassment:</strong> Attacks based on race, religion, gender, and cyberbullying.</li>                                                                          
        <li><strong>Illegal Activities:</strong> Drug/weapon trade and exposing others' private data (Doxxing).</li>                                                                               
      </ul>                                                                                                                                                                                        
    </div>                                                                                                                                                                                         
                                                                                                                                                                                                   
    <div class="section">                                   
      <span class="section-number">Section 3</span>
      <h2>Flagging and Blocking Mechanisms</h2>
      <p>Users can instantly report inappropriate content using the <strong>"Report"</strong> button and block unwanted users via the <strong>"Block"</strong> button. Our moderation team reviews 
  reported content within 24 hours.</p>                                                                                                                                                            
    </div>                                                                                                                                                                                         
                                                                                                                                                                                                   
    <div class="section">                                   
      <span class="section-number">Section 4</span>
      <h2>Digital Jury and Disclaimer</h2>                                                                                                                                                         
      <p>SenC is an opinion-sharing platform. User votes (Buy/Don't Buy, Go/Don't Go, etc.) are for advisory purposes only. You are solely responsible for any personal or financial decisions made
   based on these votes.</p>                                                                                                                                                                       
    </div>                                                  
                                                                                                                                                                                                   
    <div class="section">                                                                                                                                                                          
      <span class="section-number">Section 5</span>
      <h2>Subscriptions and Refunds</h2>                                                                                                                                                           
                                                            
      <div class="highlight-box">
        <div class="plan-name">SenC Gold</div>
        <div class="price">$4.99 <span>/ month</span></div>                                                                                                                                        
      </div>                                                                                                                                                                                       
                                                                                                                                                                                                   
      <p>Payment is charged to your Apple ID or Google Play account at the time of purchase confirmation. Subscriptions automatically renew at the same price each month unless cancelled at least 
  24 hours before the end of the current billing period.</p>
                                                                                                                                                                                                   
      <div class="steps">                                   
        <div class="step">
          <div class="step-icon ios"></div>
          <div class="step-content">                                                                                                                                                               
            <strong>Cancel on iOS</strong>
            <p>Settings → tap your name → <code>Subscriptions</code> → SenC → <code>Cancel Subscription</code></p>                                                                                 
          </div>                                                                                                                                                                                   
        </div>
        <div class="step">                                                                                                                                                                         
          <div class="step-icon android">🤖</div>           
          <div class="step-content">
            <strong>Cancel on Android</strong>
            <p>Google Play Store → profile icon → <code>Payments &amp; subscriptions</code> → Subscriptions → SenC → <code>Cancel subscription</code></p>
          </div>                                                                                                                                                                                   
        </div>
      </div>                                                                                                                                                                                       
                                                            
      <div class="warning-box">
        <strong>Non-Refundable:</strong> Subscription fees are non-refundable. If your account is terminated for violating community rules, any remaining subscription period will be forfeited.
  Refund requests may be submitted directly to Apple or Google per their respective policies.                                                                                                      
      </div>
    </div>                                                                                                                                                                                         
                                                            
    <div class="section">                                                                                                                                                                          
      <span class="section-number">Section 6</span>
      <h2>Content License</h2>                                                                                                                                                                     
      <p>You own the copyright to the images you upload. However, by uploading, you grant us a worldwide, royalty-free license to display these images within the App's voting feed.</p>
    </div>                                                                                                                                                                                         
   
    <div class="section">                                                                                                                                                                          
      <span class="section-number">Section 7</span>         
      <h2>Governing Law</h2>
      <p>These terms are governed by the laws of the Republic of Turkey, and Istanbul Courts have exclusive jurisdiction.</p>
    </div>                                                                                                                                                                                         
   
    <div class="section">                                                                                                                                                                          
      <span class="section-number">Section 8</span>         
      <h2>Privacy Policy</h2>                                                                                                                                                                      
      <p>For information on how we collect and use your data, please see our <a href="https://hakan616184.github.io/SenC/privacy-policy" style="color:#a855f7;">Privacy Policy</a>.</p>
    </div>                                                                                                                                                                                         
   
  </div>                                                                                                                                                                                           
                                                            
  <footer>
    <p>© 2026 Aquaguard Teknoloji Bilgisayar Ltd. Şti. — All rights reserved.</p>
    <p>                                                                                                                                                                                            
      <a href="https://hakan616184.github.io/SenC/terms-of-service">Terms of Service</a>
      &nbsp;·&nbsp;                                                                                                                                                                                
      <a href="https://hakan616184.github.io/SenC/privacy-policy">Privacy Policy</a>
    </p>                                                                                                                                                                                           
  </footer>
                                                                                                                                                                                                   
  </body>                                                   
  </html>
