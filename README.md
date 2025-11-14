# Clear-book-website-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ClearBooks — Professional Bookkeeping & QuickBooks ProAdvisor</title>
    <style>
        :root{ 
            --bg:#f7fafc; 
            --card:#ffffff; 
            --muted:#6b7280; 
            --brand:#0f766e; 
            --accent:#06b6d4; 
            --glass: rgba(255,255,255,0.6); 
            font-family: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial; 
        } 
        *{box-sizing:border-box} 
        body{margin:0;background:linear-gradient(180deg,var(--bg),#eef2f7);color:#0f172a;} 
        .container{max-width:1100px;margin:0 auto;padding:48px 20px} 
        header{display:flex;justify-content:space-between;align-items:center;margin-bottom:28px} 
        .logo{display:flex;align-items:center;gap:12px} 
        .logo-mark{width:48px;height:48px;border-radius:10px;background:linear-gradient(135deg,var(--brand),var(--accent));display:grid;place-items:center;color:white;font-weight:700} 
        nav a{margin-left:18px;color:var(--muted);text-decoration:none;font-weight:600} 
        .hero{display:grid;grid-template-columns:1fr 420px;gap:32px;align-items:center;margin-bottom:32px} 
        .hero h1{font-size:36px;margin:0 0 12px;line-height:1.05} 
        .hero p{margin:0 0 20px;color:var(--muted)} 
        .cta-row{display:flex;gap:12px} 
        .btn{background:var(--brand);color:white;padding:12px 18px;border-radius:10px;text-decoration:none;font-weight:700;border:none;cursor:pointer;display:inline-block;text-align:center;} 
        .btn-outline{background:transparent;border:2px solid var(--brand);color:var(--brand);padding:10px 16px;border-radius:10px} 
        .card{background:var(--card);border-radius:14px;padding:20px;box-shadow:0 6px 20px rgba(15,23,42,0.06)} 
        .features{display:grid;grid-template-columns:repeat(2,1fr);gap:14px;margin-bottom:28px} 
        .feature{display:flex;gap:12px;align-items:flex-start} 
        .icon{width:44px;height:44px;border-radius:10px;background:var(--glass);display:grid;place-items:center;font-weight:700} 
        .quickbooks-badge{display:flex;gap:10px;align-items:center;margin-top:12px} 
        .services{display:grid;grid-template-columns:repeat(3,1fr);gap:16px;margin-top:18px} 
        .service{padding:18px;border-radius:12px;background:linear-gradient(180deg,#fff,#fbfdfe);border:1px solid #eef3f3} 
        .two-col{display:grid;grid-template-columns:1fr 1fr;gap:18px} 
        footer{margin-top:36px;padding:28px 0;color:var(--muted);border-top:1px solid #e6eef0} 
        .contact-form input,.contact-form textarea{width:100%;padding:12px;border:1px solid #e6eef0;border-radius:8px;margin-bottom:10px;font-size:14px} 
        .small{font-size:13px;color:var(--muted)} 
        .sr-only {
            position: absolute;
            width: 1px;
            height: 1px;
            padding: 0;
            margin: -1px;
            overflow: hidden;
            clip: rect(0, 0, 0, 0);
            white-space: nowrap;
            border: 0;
        }
        @media (max-width:900px){ 
            .hero{grid-template-columns:1fr;} 
            .services{grid-template-columns:1fr} 
            .two-col{grid-template-columns:1fr} 
            nav{display:none} 
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo">
                <div class="logo-mark">CB</div>
                <div>ClearBooks</div>
            </div>
            <nav>
                <a href="#services">Services</a>
                <a href="#about">About</a>
                <a href="#pricing">Pricing</a>
                <a href="#contact">Contact</a>
            </nav>
        </header>

        <section class="hero">
            <div>
                <h1>Accurate bookkeeping that gives you clarity and control</h1>
                <p>I'm a Bookkeeper and Certified QuickBooks ProAdvisor with experience as a Revenue Audit Associate. I keep your books accurate and up to date so you can make confident decisions and focus on growing your business.</p>
                <div class="cta-row">
                    <a class="btn" href="#contact">Get a free consultation</a>
                    <a class="btn-outline" href="#services">See services</a>
                </div>
                <div class="card" style="margin-top:20px;">
                    <div style="display:flex;justify-content:space-between;align-items:center">
                        <div>
                            <div style="font-weight:700">Why work with me</div>
                            <div class="small">Detail-oriented · Reliable · Committed to accuracy & confidentiality</div>
                        </div>
                        <div class="quickbooks-badge">
                            <img alt="QuickBooks ProAdvisor badge" src="https://via.placeholder.com/84x28?text=QBO" style="height:28px;">
                        </div>
                    </div>
                    <div class="features" style="margin-top:12px">
                        <div class="feature">
                            <div class="icon">✓</div>
                            <div>
                                <strong>QuickBooks Management</strong>
                                <div class="small">Organized set-up, chart of accounts and clean-up</div>
                            </div>
                        </div>
                        <div class="feature">
                            <div class="icon">🔁</div>
                            <div>
                                <strong>Reconciliations</strong>
                                <div class="small">Accounts & bank statements matched every period</div>
                            </div>
                        </div>
                        <div class="feature">
                            <div class="icon">📊</div>
                            <div>
                                <strong>Financial Reporting</strong>
                                <div class="small">P&L, balance sheet, cash flow and custom reports</div>
                            </div>
                        </div>
                        <div class="feature">
                            <div class="icon">💸</div>
                            <div>
                                <strong>A/P & A/R</strong>
                                <div class="small">Invoice management, vendor payments and collections</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <aside>
                <div class="card">
                    <h3 style="margin-top:0;">Bookkeeping Snapshot</h3>
                    <div class="small">What you'll get in a typical month</div>
                    <ul style="padding-left:18px;margin-top:12px;color:var(--muted)">
                        <li>Weekly transaction uploads & categorization</li>
                        <li>Monthly bank & credit card reconciliations</li>
                        <li>Monthly financial statements & commentary</li>
                        <li>Accounts payable & receivable oversight</li>
                    </ul>
                    <div style="margin-top:14px">
                        <a class="btn" href="#contact">Schedule a call</a>
                    </div>
                </div>
                <div class="card" style="margin-top:14px">
                    <h4 style="margin:0 0 8px">Typical clients</h4>
                    <div class="small">Service businesses, e-commerce, professional services, and startups that want clean, compliant books without hiring in-house.</div>
                </div>
            </aside>
        </section>

        <section id="services">
            <h2 style="margin-bottom:6px">Services</h2>
            <div class="small">Practical bookkeeping services tailored to your business needs.</div>
            <div class="services">
                <div class="service">
                    <h3 style="margin-top:0">Full-Service Bookkeeping</h3>
                    <p class="small">End-to-end bookkeeping, monthly close, reconciliations, and financial statements.</p>
                </div>
                <div class="service">
                    <h3 style="margin-top:0">QuickBooks Cleanup & Setup</h3>
                    <p class="small">Fix chart of accounts, reclassify transactions, and configure integrations.</p>
                </div>
                <div class="service">
                    <h3 style="margin-top:0">Accounts Payable & Receivable</h3>
                    <p class="small">Invoice management, vendor payments, cash flow monitoring and collections support.</p>
                </div>
                <div class="service">
                    <h3 style="margin-top:0">Financial Reporting & Advisory</h3>
                    <p class="small">Custom reports, KPI dashboards and monthly commentary to guide decisions.</p>
                </div>
                <div class="service">
                    <h3 style="margin-top:0">Audit & Compliance Support</h3>
                    <p class="small">Supporting documentation, reconciliations and liaison with auditors.</p>
                </div>
                <div class="service">
                    <h3 style="margin-top:0">On-Demand Projects</h3>
                    <p class="small">One-off cleanups, conversions, or special reporting projects.</p>
                </div>
            </div>
        </section>

        <section id="about" style="margin-top:26px">
            <div class="two-col">
                <div class="card">
                    <h3 style="margin-top:0">About Me</h3>
                    <p class="small">I'm a Bookkeeper and Certified QuickBooks ProAdvisor with experience as a Revenue Audit Associate. I help business owners and entrepreneurs gain control and clarity over their finances — so you can make confident decisions and focus on growing your business.</p>
                    <ul style="padding-left:18px;color:var(--muted)">
                        <li>Certified QuickBooks ProAdvisor</li>
                        <li>Revenue Audit experience — strong compliance focus</li>
                        <li>Confidential & detail-oriented approach</li>
                    </ul>
                </div>
                <div class="card">
                    <h3 style="margin-top:0">Client process</h3>
                    <ol style="padding-left:18px;color:var(--muted)">
                        <li>Discovery call to understand current systems and needs</li>
                        <li>Onboarding & QuickBooks access/setup</li>
                        <li>Ongoing bookkeeping, monthly close and reporting</li>
                        <li>Quarterly review and recommendations</li>
                    </ol>
                </div>
            </div>
        </section>

        <section id="pricing" style="margin-top:26px">
            <h2>Pricing</h2>
            <div class="small">Transparent packages — custom quotes available for complex needs.</div>
            <div style="display:grid;grid-template-columns:repeat(3,1fr);gap:12px;margin-top:12px">
                <div class="card">
                    <h3 style="margin-top:0">Starter</h3>
                    <div class="small">Ideal for very small businesses</div>
                    <ul class="small" style="padding-left:18px;color:var(--muted)">
                        <li>Monthly bookkeeping (&lt;=50 transactions)</li>
                        <li>Basic reports</li>
                        <li>Email support</li>
                    </ul>
                    <div style="margin-top:12px;font-weight:700">From $250 / month</div>
                </div>
                <div class="card">
                    <h3 style="margin-top:0">Growth</h3>
                    <div class="small">For growing businesses</div>
                    <ul class="small" style="padding-left:18px;color:var(--muted)">
                        <li>Monthly bookkeeping (&lt;=250 transactions)</li>
                        <li>Monthly statements & commentary</li>
                        <li>Quarterly review</li>
                    </ul>
                    <div style="margin-top:12px;font-weight:700">From $600 / month</div>
                </div>
                <div class="card">
                    <h3 style="margin-top:0">Custom</h3>
                    <div class="small">Tailored to complex bookkeeping or audit support</div>
                    <div style="margin-top:12px;font-weight:700">Custom quote</div>
                </div>
            </div>
        </section>

        <div class="card" style="margin-top:28px">
            <h3 style="margin-top:0">Why Choose Me</h3>
            <div class="small">
                Certified QuickBooks ProAdvisor — expert setup, cleanup, and monthly management.<br>
                Revenue Audit background — strong compliance, accuracy, and documentation skills.<br>
                Reliable & responsive — easy communication and fast turnaround.<br>
                Detail‑oriented — every transaction is categorized correctly the first time.<br>
                Confidential & secure — your financial data is always protected.
            </div>
        </div>

        <section id="contact" style="margin-top:28px">
            <h2>Contact</h2>
            <div class="small">Ready to simplify your bookkeeping? Send a message or book a free consultation.</div>
            
            <div class="two-col" style="margin-top:12px">
                <div class="card contact-form">
                    <form action="https://formspree.io/f/xwpalnlr" method="POST" id="contact-form">
                        <label for="name" class="sr-only">Full name</label>
                        <input type="text" id="name" name="name" placeholder="Full name" required>
                        
                        <label for="email" class="sr-only">Email</label>
                        <input type="email" id="email" name="email" placeholder="Email" required>
                        
                        <label for="company" class="sr-only">Company</label>
                        <input type="text" id="company" name="company" placeholder="Company (optional)">
                        
                        <label for="message" class="sr-only">Message</label>
                        <textarea id="message" name="message" rows="6" placeholder="How can I help you?" required></textarea>
                        
                        <div style="display:flex;gap:8px;align-items:center">
                            <button class="btn" type="submit" id="submit-btn">Send message</button>
                            <div class="small">Or email: <a href="mailto:clearbookpro@gmail.com">clearbookpro@gmail.com</a></div>
                        </div>
                        
                        <div id="success-message" style="display:none;background:#ecfdf5;border:1px solid #a7f3d0;color:#065f46;padding:12px 14px;border-radius:8px;font-weight:600;margin-top:12px;align-items:center;gap:8px;">
                            ✓ Thank you! Your message has been sent.
                        </div>
                    </form>
                </div>
                
                <div>
                    <div class="card">
                        <h3 style="margin-top:0">Quick FAQ</h3>
                        <div class="small"><strong>How do we start?</strong> Book a discovery call or send your QuickBooks invite. I'll assess and deliver an onboarding plan.</div>
                        <div style="height:10px"></div>
                        <div class="small"><strong>Is my data secure?</strong> Yes — I maintain confidentiality, limited user access and follow best practices.</div>
                        <div style="height:10px"></div>
                        <div class="small"><strong>Do you work remotely?</strong> Yes — with cloud QuickBooks and secure file transfers.</div>
                    </div>
                    <div style="height:8px"></div>
                    <div class="small" style="color:var(--muted)">"Fast turnaround and sharp attention to detail for audit prep." — B. Client</div>
                </div>
            </div>
        </section>

        <footer>
            <div style="display:flex;justify-content:space-between;align-items:center;gap:16px;flex-wrap:wrap">
                <div>
                    © <span id="year"></span> ClearBooks — Bookkeeping & QuickBooks ProAdvisor
                </div>
                <div class="small">Designed for small businesses. <a href="#contact">Contact</a></div>
            </div>
        </footer>
    </div>

    <script>
        // Set current year in footer
        document.getElementById('year').textContent = new Date().getFullYear();
        
        // Form submission handler
        const form = document.getElementById('contact-form');
        const successMessage = document.getElementById('success-message');
        const submitBtn = document.getElementById('submit-btn');
        
        form.addEventListener('submit', async (e) => {
            e.preventDefault();
            const originalText = submitBtn.textContent;
            
            // Show loading state
            submitBtn.textContent = 'Sending...';
            submitBtn.disabled = true;
            successMessage.style.display = 'none';
            
            try {
                const data = new FormData(form);
                const response = await fetch(form.action, {
                    method: 'POST',
                    body: data,
                    headers: { 'Accept': 'application/json' }
                });
                
                if (response.ok) {
                    successMessage.style.display = 'flex';
                    form.reset();
                } else {
                    alert('There was a problem sending your message. Please try again.');
                }
            } catch (error) {
                console.error('Form submission error:', error);
                alert('There was a problem sending your message. Please try again.');
            } finally {
                submitBtn.textContent = originalText;
                submitBtn.disabled = false;
            }
        });
    </script>
</body>
</html>
