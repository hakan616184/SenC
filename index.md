 <html lang="en">
  <head>                                                                                                                                                                                           
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />                                                                                                                       
    <title>Legal Information Center – SenC</title>
    <style>                                                                                                                                                                                        
      * { margin: 0; padding: 0; box-sizing: border-box; }
                                                                                                                                                                                                   
      body {           
        font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
        background: #0f0f0f;                                                                                                                                                                       
        color: #e0e0e0;
        line-height: 1.7;                                                                                                                                                                          
        min-height: 100vh;
        display: flex;                                                                                                                                                                             
        flex-direction: column;
      }

      header {
        background: #1a1a1a;
        border-bottom: 1px solid #2a2a2a;                                                                                                                                                          
        padding: 20px 0;
        text-align: center;                                                                                                                                                                        
      }                                                     

      header .logo {
        font-size: 26px;
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
        background: linear-gradient(135deg, #1a0a2e 0%, #0f0820 60%, #0f0f0f 100%);
        padding: 72px 24px 60px;                                                                                                                                                                   
        text-align: center;
        border-bottom: 1px solid #2a2a2a;                                                                                                                                                          
      }                                                     
                                                                                                                                                                                                   
      .hero .badge {                                        
        display: inline-block;
        background: rgba(168, 85, 247, 0.15);
        border: 1px solid rgba(168, 85, 247, 0.4);                                                                                                                                                 
        color: #c084fc;
        font-size: 12px;                                                                                                                                                                           
        font-weight: 600;                                                                                                                                                                          
        padding: 5px 14px;
        border-radius: 20px;                                                                                                                                                                       
        margin-bottom: 20px;                                
        letter-spacing: 1px;
        text-transform: uppercase;                                                                                                                                                                 
      }
                                                                                                                                                                                                   
      .hero h1 {                                            
        font-size: 36px;
        font-weight: 800;
        color: #ffffff;                                                                                                                                                                            
        margin-bottom: 16px;
        letter-spacing: -0.5px;                                                                                                                                                                    
      }                                                     

      .hero p {
        font-size: 16px;
        color: #888;
        max-width: 480px;                                                                                                                                                                          
        margin: 0 auto;
      }                                                                                                                                                                                            
                                                            
      .container {
        max-width: 680px;
        margin: 0 auto;
        padding: 52px 24px 80px;
        flex: 1;                                                                                                                                                                                   
      }
                                                                                                                                                                                                   
      .section-title {                                                                                                                                                                             
        font-size: 12px;
        font-weight: 700;                                                                                                                                                                          
        color: #555;                                        
        text-transform: uppercase;
        letter-spacing: 1.5px;
        margin-bottom: 16px;                                                                                                                                                                       
      }
                                                                                                                                                                                                   
      .card-grid {                                          
        display: flex;
        flex-direction: column;
        gap: 14px;
        margin-bottom: 40px;
      }                                                                                                                                                                                            
  
      .card {                                                                                                                                                                                      
        display: flex;                                      
        align-items: center;
        gap: 20px;
        background: #1a1a1a;
        border: 1px solid #2a2a2a;                                                                                                                                                                 
        border-radius: 16px;
        padding: 22px 24px;                                                                                                                                                                        
        text-decoration: none;                              
        color: inherit;
        transition: border-color 0.2s, background 0.2s;                                                                                                                                            
      }
                                                                                                                                                                                                   
      .card:hover {                                         
        border-color: #a855f7;
        background: #1e1428;
      }                                                                                                                                                                                            
  
      .card-icon {                                                                                                                                                                                 
        width: 52px;                                        
        height: 52px;
        border-radius: 14px;                                                                                                                                                                       
        display: flex;
        align-items: center;                                                                                                                                                                       
        justify-content: center;                            
        font-size: 24px;
        flex-shrink: 0;
      }
                                                                                                                                                                                                   
      .card-icon.purple { background: linear-gradient(135deg, #4c1d95, #7c3aed); }
      .card-icon.pink   { background: linear-gradient(135deg, #831843, #be185d); }                                                                                                                 
                                                                                                                                                                                                   
      .card-body { flex: 1; }
                                                                                                                                                                                                   
      .card-body h3 {                                                                                                                                                                              
        font-size: 16px;
        font-weight: 700;                                                                                                                                                                          
        color: #ffffff;                                     
        margin-bottom: 4px;
      }

      .card-body p {
        font-size: 13px;
        color: #777;                                                                                                                                                                               
      }
                                                                                                                                                                                                   
      .card-arrow {                                         
        font-size: 20px;
        color: #444;
        flex-shrink: 0;
      }                                                                                                                                                                                            
  
      .card:hover .card-arrow { color: #a855f7; }                                                                                                                                                  
                                                            
      .contact-box {
        background: #1a1a1a;
        border: 1px solid #2a2a2a;
        border-radius: 16px;                                                                                                                                                                       
        padding: 28px 24px;
        text-align: center;                                                                                                                                                                        
      }                                                     

      .contact-box .icon {
        font-size: 32px;
        margin-bottom: 12px;
      }                                                                                                                                                                                            
  
      .contact-box h3 {                                                                                                                                                                            
        font-size: 16px;                                    
        font-weight: 700;
        color: #fff;
        margin-bottom: 8px;
      }                                                                                                                                                                                            
  
      .contact-box p {                                                                                                                                                                             
        font-size: 14px;                                    
        color: #777;
        margin-bottom: 16px;
      }

      .contact-box a {
        display: inline-block;
        background: linear-gradient(135deg, #a855f7, #ec4899);                                                                                                                                     
        color: #fff;
        font-size: 14px;                                                                                                                                                                           
        font-weight: 600;                                   
        padding: 10px 24px;                                                                                                                                                                        
        border-radius: 10px;
        text-decoration: none;                                                                                                                                                                     
      }                                                     

      .contact-box a:hover { opacity: 0.9; }                                                                                                                                                       
  
      footer {                                                                                                                                                                                     
        background: #1a1a1a;                                
        border-top: 1px solid #2a2a2a;
        padding: 28px 24px;
        text-align: center;                                                                                                                                                                        
      }
                                                                                                                                                                                                   
      footer p {                                            
        font-size: 13px;
        color: #444;
      }

      @media (max-width: 600px) {                                                                                                                                                                  
        .hero h1 { font-size: 26px; }
        .card { padding: 18px; gap: 14px; }                                                                                                                                                        
        .card-icon { width: 44px; height: 44px; font-size: 20px; border-radius: 12px; }                                                                                                            
      }
    </style>                                                                                                                                                                                       
  </head>                                                   
  <body>                                                                                                                                                                                           
                                                            
  <header>
    <div class="logo"><span>SenC</span></div>
  </header>

  <div class="hero">                                                                                                                                                                               
    <div class="badge">Legal Center</div>
    <h1>Legal Information</h1>                                                                                                                                                                     
    <p>To ensure a safe and transparent experience for all users, our legal documents are available below.</p>
  </div>                                                                                                                                                                                           
  
  <div class="container">                                                                                                                                                                          
                                                            
    <p class="section-title">Documents & Policies</p>                                                                                                                                              
  
    <div class="card-grid">                                                                                                                                                                        
      <a class="card" href="https://hakan616184.github.io/SenC/privacy-policy">
        <div class="card-icon purple">🔒</div>                                                                                                                                                     
        <div class="card-body">
          <h3>Privacy Policy</h3>                                                                                                                                                                  
          <p>Learn how your data is collected, processed, and protected.</p>
        </div>                                                                                                                                                                                     
        <div class="card-arrow">›</div>
      </a>                                                                                                                                                                                         
                                                            
      <a class="card" href="https://hakan616184.github.io/SenC/terms-of-service">                                                                                                                  
        <div class="card-icon pink">📄</div>
        <div class="card-body">                                                                                                                                                                    
          <h3>Terms of Service</h3>                         
          <p>Review our community rules, subscription details, and user agreement.</p>
        </div>                                                                                                                                                                                     
        <div class="card-arrow">›</div>
      </a>                                                                                                                                                                                         
    </div>                                                  

    <div class="contact-box">                                                                                                                                                                      
      <div class="icon">✉️ </div>
      <h3>Contact & Support</h3>                                                                                                                                                                   
      <p>Have a question or legal inquiry? We're here to help.</p>
      <a href="mailto:support@aquaguardwd.com">support@aquaguardwd.com</a>                                                                                                                         
    </div>
                                                                                                                                                                                                   
  </div>                                                    

  <footer>
    <p>© 2026 Aquaguard Teknoloji Bilgisayar Limited Şirketi. All rights reserved.</p>
  </footer>                                                                                                                                                                                        
  
  </body>                                                                                                                                                                                          
  </html> 
