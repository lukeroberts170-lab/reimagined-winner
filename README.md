# www.LCRPlumbingandMaintance.com
Hi 👋 this is Luke from LCR Plumbing &amp; Maintenance. I handle plumbing, painting, and general maintenance — reliable and affordable.
logo LCR Plumbing And Maintenance 
<!doctype html>
<html lang="en">
 <head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>LCR Plumbing and Maintenance - East London, South Africa</title>
  <meta name="description" content="Professional plumbing, painting, and general maintenance services in East London, South Africa. Contact LCR Plumbing and Maintenance for reliable home and business solutions.">
  <meta name="keywords" content="plumber East London, painter East London, maintenance services, plumbing repairs, painting services, South Africa">
  <script src="/_sdk/element_sdk.js"></script>
  <style>
        body {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: #333;
        }
        
        * {
            box-sizing: border-box;
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        /* Header */
        header {
            background: linear-gradient(135deg, #1e40af 0%, #3b82f6 100%);
            color: white;
            padding: 2rem 0;
            text-align: center;
            position: relative;
            overflow: hidden;
        }

        header::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: url('data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><defs><pattern id="grid" width="10" height="10" patternUnits="userSpaceOnUse"><path d="M 10 0 L 0 0 0 10" fill="none" stroke="rgba(255,255,255,0.1)" stroke-width="0.5"/></pattern></defs><rect width="100" height="100" fill="url(%23grid)"/></svg>');
            opacity: 0.3;
        }

        .header-content {
            position: relative;
            z-index: 1;
        }

        h1 {
            font-size: 3rem;
            margin: 0 0 0.5rem 0;
            font-weight: 700;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.3);
        }

        .tagline {
            font-size: 1.2rem;
            margin: 0;
            opacity: 0.9;
        }

        /* Services Section */
        .services {
            padding: 4rem 0;
            background: #f8fafc;
        }

        .services h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #1e40af;
        }

        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }

        .service-card {
            background: white;
            padding: 2rem;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.1);
            text-align: center;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
            border: 2px solid transparent;
        }

        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
            border-color: #3b82f6;
        }

        .service-icon {
            width: 80px;
            height: 80px;
            margin: 0 auto 1.5rem;
            background: #3b82f6;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }

        .service-card h3 {
            font-size: 1.5rem;
            margin-bottom: 1rem;
            color: #1e40af;
        }

        .service-card p {
            color: #64748b;
            line-height: 1.6;
        }

        /* Contact Section */
        .contact {
            padding: 4rem 0;
            background: white;
        }

        .contact h2 {
            text-align: center;
            font-size: 2.5rem;
            margin-bottom: 3rem;
            color: #1e40af;
        }

        .contact-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 3rem;
            align-items: start;
        }

        .contact-info {
            background: #f8fafc;
            padding: 2rem;
            border-radius: 12px;
            border-left: 4px solid #3b82f6;
        }

        .contact-item {
            display: flex;
            align-items: center;
            margin-bottom: 1.5rem;
            padding: 1rem;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.05);
        }

        .contact-item:last-child {
            margin-bottom: 0;
        }

        .contact-icon {
            width: 40px;
            height: 40px;
            background: #3b82f6;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-right: 1rem;
            flex-shrink: 0;
        }

        .contact-text {
            flex: 1;
        }

        .contact-text strong {
            display: block;
            color: #1e40af;
            margin-bottom: 0.25rem;
        }

        .contact-text span {
            color: #64748b;
        }

        /* Map Section */
        .map-container {
            background: #f8fafc;
            padding: 2rem;
            border-radius: 12px;
            text-align: center;
        }

        .map-placeholder {
            width: 100%;
            height: 300px;
            background: linear-gradient(135deg, #e2e8f0 0%, #cbd5e1 100%);
            border-radius: 8px;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            border: 2px dashed #94a3b8;
            margin-bottom: 1rem;
        }

        .map-icon {
            width: 60px;
            height: 60px;
            background: #3b82f6;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            margin-bottom: 1rem;
        }

        .map-text {
            color: #64748b;
            font-size: 1.1rem;
            margin-bottom: 0.5rem;
        }

        .map-subtext {
            color: #94a3b8;
            font-size: 0.9rem;
        }

        /* Footer */
        footer {
            background: #1e293b;
            color: white;
            text-align: center;
            padding: 2rem 0;
        }

        .footer-content {
            display: flex;
            flex-direction: column;
            align-items: center;
            gap: 1rem;
        }

        .footer-links {
            display: flex;
            gap: 2rem;
            flex-wrap: wrap;
            justify-content: center;
        }

        .footer-links a {
            color: #94a3b8;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        .footer-links a:hover {
            color: #3b82f6;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            h1 {
                font-size: 2rem;
            }
            
            .tagline {
                font-size: 1rem;
            }
            
            .services h2,
            .contact h2 {
                font-size: 2rem;
            }
            
            .service-card,
            .contact-info {
                padding: 1.5rem;
            }
            
            .contact-grid {
                gap: 2rem;
            }
            
            .footer-links {
                flex-direction: column;
                gap: 1rem;
            }
        }

        @media (max-width: 480px) {
            .container {
                padding: 0 15px;
            }
            
            header {
                padding: 1.5rem 0;
            }
            
            .services,
            .contact {
                padding: 3rem 0;
            }
        }
    </style>
  <style>@view-transition { navigation: auto; }</style>
  <script src="/_sdk/data_sdk.js" type="text/javascript"></script>
  <script src="https://cdn.tailwindcss.com" type="text/javascript"></script>
 </head>
 <body>
  <header>
   <div class="container">
    <div class="header-content">
     <h1 id="company-name">LCR PLUMBING AND MAINTENANCE</h1>
     <p class="tagline" id="tagline">Professional Services in East London, South Africa</p>
    </div>
   </div>
  </header>
  <main>
   <section class="services">
    <div class="container">
     <h2 id="services-title">Our Services</h2>
     <div class="services-grid">
      <div class="service-card">
       <div class="service-icon">
        <svg width="40" height="40" fill="white" viewbox="0 0 24 24"><path d="M12 2C6.48 2 2 6.48 2 12s4.48 10 10 10 10-4.48 10-10S17.52 2 12 2zm-1 17.93c-3.94-.49-7-3.85-7-7.93 0-.62.08-1.21.21-1.79L9 15v1c0 1.1.9 2 2 2v1.93zm6.9-2.54c-.26-.81-1-1.39-1.9-1.39h-1v-3c0-.55-.45-1-1-1H8v-2h2c.55 0 1-.45 1-1V7h2c1.1 0 2-.9 2-2v-.41c2.93 1.19 5 4.06 5 7.41 0 2.08-.8 3.97-2.1 5.39z" />
        </svg>
       </div>
       <h3 id="plumbing-title">Plumbing Services</h3>
       <p>Complete plumbing solutions including repairs, installations, leak detection, pipe replacements, and emergency plumbing services for residential and commercial properties.</p>
      </div>
      <div class="service-card">
       <div class="service-icon">
        <svg width="40" height="40" fill="white" viewbox="0 0 24 24"><path d="M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z" />
        </svg>
       </div>
       <h3 id="painting-title">Painting Services</h3>
       <p>Professional interior and exterior painting services using high-quality paints and materials. We transform your spaces with expert color consultation and flawless finishes.</p>
      </div>
      <div class="service-card">
       <div class="service-icon">
        <svg width="40" height="40" fill="white" viewbox="0 0 24 24"><path d="M22.7 19l-9.1-9.1c.9-2.3.4-5-1.5-6.9-2-2-5-2.4-7.4-1.3L9 6 6 9 1.6 4.7C.4 7.1.9 10.1 2.9 12.1c1.9 1.9 4.6 2.4 6.9 1.5l9.1 9.1c.4.4 1 .4 1.4 0l2.3-2.3c.5-.4.5-1.1.1-1.4z" />
        </svg>
       </div>
       <h3 id="maintenance-title">General Maintenance</h3>
       <p>Comprehensive maintenance services including electrical work, carpentry, tiling, roofing repairs, and general handyman services to keep your property in perfect condition.</p>
      </div>
     </div>
    </div>
   </section>
   <section class="contact">
    <div class="container">
     <h2 id="contact-title">Contact Us</h2>
     <div class="contact-grid">
      <div class="contact-info">
       <div class="contact-item">
        <div class="contact-icon">
         <svg width="20" height="20" fill="white" viewbox="0 0 24 24"><path d="M6.62 10.79c1.44 2.83 3.76 5.14 6.59 6.59l2.2-2.2c.27-.27.67-.36 1.02-.24 1.12.37 2.33.57 3.57.57.55 0 1 .45 1 1V20c0 .55-.45 1-1 1-9.39 0-17-7.61-17-17 0-.55.45-1 1-1h3.5c.55 0 1 .45 1 1 0 1.25.2 2.45.57 3.57.11.35.03.74-.25 1.02l-2.2 2.2z" />
         </svg>
        </div>
        <div class="contact-text"><strong>Phone</strong> <span id="phone-number">072 107 3968</span>
        </div>
       </div>
       <div class="contact-item">
        <div class="contact-icon">
         <svg width="20" height="20" fill="white" viewbox="0 0 24 24"><path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z" />
         </svg>
        </div>
        <div class="contact-text"><strong>Email</strong> <span id="email-address">lukeroberts170@gmail.com</span>
        </div>
       </div>
       <div class="contact-item">
        <div class="contact-icon">
         <svg width="20" height="20" fill="white" viewbox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z" />
         </svg>
        </div>
        <div class="contact-text"><strong>Service Area</strong> <span id="location-text">East London, South Africa</span>
        </div>
       </div>
      </div>
      <div class="map-container">
       <div class="map-placeholder">
        <div class="map-icon">
         <svg width="30" height="30" fill="white" viewbox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z" />
         </svg>
        </div>
        <div class="map-text">
         Find Us on Google Maps
        </div>
        <div class="map-subtext">
         Search "LCR Plumbing East London" to locate us
        </div>
       </div>
       <p style="color: #64748b; margin: 0; font-size: 0.9rem;"><strong>SEO Tip:</strong> When customers search for "plumbers near me" or "painters East London" on Google Maps, make sure to create a Google My Business profile with your business details to appear in local search results.</p>
      </div>
     </div>
    </div>
   </section>
  </main>
  <footer>
   <div class="container">
    <div class="footer-content">
     <div class="footer-links"><span>© 2024 LCR Plumbing and Maintenance</span> <span>East London, South Africa</span> <span>Professional • Reliable • Affordable</span>
     </div>
    </div>
   </div>
  </footer>
  <script>
        const defaultConfig = {
            company_name: "LCR PLUMBING AND MAINTENANCE",
            tagline: "Professional Services in East London, South Africa",
            services_title: "Our Services",
            plumbing_title: "Plumbing Services",
            painting_title: "Painting Services", 
            maintenance_title: "General Maintenance",
            contact_title: "Contact Us",
            phone_number: "072 107 3968",
            email_address: "lukeroberts170@gmail.com",
            location_text: "East London, South Africa",
            primary_color: "#3b82f6",
            secondary_color: "#1e40af",
            background_color: "#f8fafc",
            text_color: "#333333",
            accent_color: "#64748b",
            font_family: "Segoe UI",
            font_size: 16
        };

        async function render(config) {
            // Update text content
            document.getElementById('company-name').textContent = config.company_name || defaultConfig.company_name;
            document.getElementById('tagline').textContent = config.tagline || defaultConfig.tagline;
            document.getElementById('services-title').textContent = config.services_title || defaultConfig.services_title;
            document.getElementById('plumbing-title').textContent = config.plumbing_title || defaultConfig.plumbing_title;
            document.getElementById('painting-title').textContent = config.painting_title || defaultConfig.painting_title;
            document.getElementById('maintenance-title').textContent = config.maintenance_title || defaultConfig.maintenance_title;
            document.getElementById('contact-title').textContent = config.contact_title || defaultConfig.contact_title;
            document.getElementById('phone-number').textContent = config.phone_number || defaultConfig.phone_number;
            document.getElementById('email-address').textContent = config.email_address || defaultConfig.email_address;
            document.getElementById('location-text').textContent = config.location_text || defaultConfig.location_text;

            // Apply colors
            const primaryColor = config.primary_color || defaultConfig.primary_color;
            const secondaryColor = config.secondary_color || defaultConfig.secondary_color;
            const backgroundColor = config.background_color || defaultConfig.background_color;
            const textColor = config.text_color || defaultConfig.text_color;
            const accentColor = config.accent_color || defaultConfig.accent_color;

            // Update CSS custom properties for colors
            document.documentElement.style.setProperty('--primary-color', primaryColor);
            document.documentElement.style.setProperty('--secondary-color', secondaryColor);
            document.documentElement.style.setProperty('--background-color', backgroundColor);
            document.documentElement.style.setProperty('--text-color', textColor);
            document.documentElement.style.setProperty('--accent-color', accentColor);

            // Apply colors to elements
            const header = document.querySelector('header');
            header.style.background = `linear-gradient(135deg, ${secondaryColor} 0%, ${primaryColor} 100%)`;

            const serviceIcons = document.querySelectorAll('.service-icon');
            serviceIcons.forEach(icon => {
                icon.style.backgroundColor = primaryColor;
            });

            const contactIcons = document.querySelectorAll('.contact-icon');
            contactIcons.forEach(icon => {
                icon.style.backgroundColor = primaryColor;
            });

            const mapIcon = document.querySelector('.map-icon');
            if (mapIcon) {
                mapIcon.style.backgroundColor = primaryColor;
            }

            const serviceCards = document.querySelectorAll('.service-card');
            serviceCards.forEach(card => {
                card.addEventListener('mouseenter', () => {
                    card.style.borderColor = primaryColor;
                });
                card.addEventListener('mouseleave', () => {
                    card.style.borderColor = 'transparent';
                });
            });

            const headings = document.querySelectorAll('h2, .service-card h3, .contact-text strong');
            headings.forEach(heading => {
                heading.style.color = secondaryColor;
            });

            const services = document.querySelector('.services');
            services.style.backgroundColor = backgroundColor;

            const contactInfo = document.querySelector('.contact-info');
            contactInfo.style.backgroundColor = backgroundColor;
            contactInfo.style.borderLeftColor = primaryColor;

            const mapContainer = document.querySelector('.map-container');
            mapContainer.style.backgroundColor = backgroundColor;

            document.body.style.color = textColor;

            // Apply font
            const customFont = config.font_family || defaultConfig.font_family;
            const baseFontStack = 'Tahoma, Geneva, Verdana, sans-serif';
            document.body.style.fontFamily = `${customFont}, ${baseFontStack}`;

            // Apply font size scaling
            const baseSize = config.font_size || defaultConfig.font_size;
            document.querySelector('h1').style.fontSize = `${baseSize * 1.875}px`; // 3rem equivalent
            document.querySelectorAll('h2').forEach(h2 => {
                h2.style.fontSize = `${baseSize * 1.5625}px`; // 2.5rem equivalent
            });
            document.querySelectorAll('.service-card h3').forEach(h3 => {
                h3.style.fontSize = `${baseSize * 0.9375}px`; // 1.5rem equivalent
            });
            document.querySelector('.tagline').style.fontSize = `${baseSize * 0.75}px`; // 1.2rem equivalent
            document.querySelectorAll('p, .contact-text span').forEach(p => {
                p.style.fontSize = `${baseSize}px`;
            });
        }

        function mapToCapabilities(config) {
            return {
                recolorables: [
                    {
                        get: () => config.primary_color || defaultConfig.primary_color,
                        set: (value) => {
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({ primary_color: value });
                            }
                        }
                    },
                    {
                        get: () => config.secondary_color || defaultConfig.secondary_color,
                        set: (value) => {
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({ secondary_color: value });
                            }
                        }
                    },
                    {
                        get: () => config.background_color || defaultConfig.background_color,
                        set: (value) => {
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({ background_color: value });
                            }
                        }
                    },
                    {
                        get: () => config.text_color || defaultConfig.text_color,
                        set: (value) => {
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({ text_color: value });
                            }
                        }
                    },
                    {
                        get: () => config.accent_color || defaultConfig.accent_color,
                        set: (value) => {
                            if (window.elementSdk) {
                                window.elementSdk.setConfig({ accent_color: value });
                            }
                        }
                    }
                ],
                borderables: [],
                fontEditable: {
                    get: () => config.font_family || defaultConfig.font_family,
                    set: (value) => {
                        if (window.elementSdk) {
                            window.elementSdk.setConfig({ font_family: value });
                        }
                    }
                },
                fontSizeable: {
                    get: () => config.font_size || defaultConfig.font_size,
                    set: (value) => {
                        if (window.elementSdk) {
                            window.elementSdk.setConfig({ font_size: value });
                        }
                    }
                }
            };
        }

        function mapToEditPanelValues(config) {
            return new Map([
                ["company_name", config.company_name || defaultConfig.company_name],
                ["tagline", config.tagline || defaultConfig.tagline],
                ["services_title", config.services_title || defaultConfig.services_title],
                ["plumbing_title", config.plumbing_title || defaultConfig.plumbing_title],
                ["painting_title", config.painting_title || defaultConfig.painting_title],
                ["maintenance_title", config.maintenance_title || defaultConfig.maintenance_title],
                ["contact_title", config.contact_title || defaultConfig.contact_title],
                ["phone_number", config.phone_number || defaultConfig.phone_number],
                ["email_address", config.email_address || defaultConfig.email_address],
                ["location_text", config.location_text || defaultConfig.location_text]
            ]);
        }

        // Initialize the Element SDK
        if (window.elementSdk) {
            window.elementSdk.init({
                defaultConfig,
                render,
                mapToCapabilities,
                mapToEditPanelValues
            });
        }

        // Initial render
        render(defaultConfig);
    </script>
 <script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'98f5eca8d6c51be9',t:'MTc2MDYwMDU5OC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
