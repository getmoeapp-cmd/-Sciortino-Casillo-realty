import { useState, useEffect } from "react";

const AGENTS = [
  {
    id: 1, name: "Michael Casillo", title: "Licensed Real Estate Professional",
    license: "FL License #BK3512847",
    bio: "With over a decade of experience in South Florida's luxury waterfront market, Michael brings unparalleled local knowledge and a client-first philosophy to every transaction. A proud Lighthouse Point resident, he understands firsthand what makes this community truly extraordinary.",
    specialty: "Luxury Waterfront & Intracoastal",
    stats: { deals: "180+", volume: "$210M+", years: "12" },
    img: "https://images.unsplash.com/photo-1560250097-0b93528c311a?w=500&h=580&fit=crop&q=80",
    phone: "(954) 555-0101", email: "michael@casillosciortino.com"
  },
  {
    id: 2, name: "Gianna Casillo", title: "Licensed Real Estate Professional",
    license: "FL License #SL3421956",
    bio: "Gianna's background in interior design and her meticulous eye for detail make her an invaluable partner for buyers seeking perfection and sellers looking to command top dollar. She brings an artisan's touch to every showing.",
    specialty: "Residential & Luxury Staging",
    stats: { deals: "145+", volume: "$95M+", years: "9" },
    img: "https://images.unsplash.com/photo-1573496359142-b8d87734a5a2?w=500&h=580&fit=crop&q=80",
    phone: "(954) 555-0102", email: "gianna@casillosciortino.com"
  },
  {
    id: 3, name: "Anthony Sciortino", title: "Licensed Real Estate Professional",
    license: "FL License #SL3398712",
    bio: "Anthony's deep network of developers, investors, and financial professionals gives his clients a strategic edge in every market cycle. From pre-construction opportunities to 1031 exchanges, Anthony is the team's deal architect.",
    specialty: "Investment & New Construction",
    stats: { deals: "220+", volume: "$175M+", years: "14" },
    img: "https://images.unsplash.com/photo-1500648767791-00dcc994a43e?w=500&h=580&fit=crop&q=80",
    phone: "(954) 555-0103", email: "anthony@casillosciortino.com"
  }
];

const LISTINGS = [
  { id:1, address:"2847 NE 26th Court", city:"Lighthouse Point, FL 33064", price:"$2,850,000", beds:4, baths:3.5, sqft:"3,240", type:"Waterfront Estate", status:"Active", agent:"Michael Casillo",
    img:"https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=600&h=400&fit=crop&q=80",
    desc:"Stunning Intracoastal estate with 80 ft of deepwater dockage, resort-style pool, and panoramic water views from every principal room." },
  { id:2, address:"1104 NE 44th Street", city:"Lighthouse Point, FL 33064", price:"$1,475,000", beds:3, baths:3, sqft:"2,180", type:"Pool Home", status:"Active", agent:"Gianna Casillo",
    img:"https://images.unsplash.com/photo-1613490493576-7fde63acd811?w=600&h=400&fit=crop&q=80",
    desc:"Beautifully renovated coastal home with open-plan living, chef's kitchen, and a private resort-style pool with tropical landscaping." },
  { id:3, address:"4520 NE 23rd Ave", city:"Pompano Beach, FL 33064", price:"$3,200,000", beds:5, baths:4.5, sqft:"4,650", type:"Deep Water Estate", status:"Active", agent:"Anthony Sciortino",
    img:"https://images.unsplash.com/photo-1580587771525-78b9dba3b914?w=600&h=400&fit=crop&q=80",
    desc:"Trophy waterfront estate on a wide canal with unobstructed views, 100 ft dock, dual boat lifts, and seamless indoor-outdoor living." },
  { id:4, address:"810 Hillsboro Mile", city:"Hillsboro Beach, FL 33062", price:"$5,750,000", beds:6, baths:6.5, sqft:"7,200", type:"Oceanfront Masterpiece", status:"Active", agent:"Michael Casillo",
    img:"https://images.unsplash.com/photo-1512917774080-9991f1c4c750?w=600&h=400&fit=crop&q=80",
    desc:"A rare oceanfront jewel on exclusive Hillsboro Mile — six bedrooms, elevator, private beach access, and next-generation smart home systems." },
  { id:5, address:"3205 NE 18th Street", city:"Pompano Beach, FL 33064", price:"$925,000", beds:3, baths:2, sqft:"1,850", type:"Canal Front", status:"Pending", agent:"Gianna Casillo",
    img:"https://images.unsplash.com/photo-1583608205776-bfd35f0d9f83?w=600&h=400&fit=crop&q=80",
    desc:"Charming canal-front home with private dock, updated interiors, and coveted ocean access through Hillsboro Inlet — in contract within 9 days." },
  { id:6, address:"2201 NE 36th Court", city:"Lighthouse Point, FL 33064", price:"$1,890,000", beds:4, baths:3, sqft:"2,980", type:"Pool & Dock", status:"Sold", agent:"Anthony Sciortino",
    img:"https://images.unsplash.com/photo-1564013799919-ab600027ffc6?w=600&h=400&fit=crop&q=80",
    desc:"Sold above asking in 11 days. A beautifully appointed Lighthouse Point canal home with private pool, dock, and quintessential South Florida lifestyle." }
];

const TESTIMONIALS = [
  { id:1, name:"Robert & Lisa Ferretti", loc:"Lighthouse Point", stars:5,
    quote:"Michael found us our dream waterfront home in just three weeks. His knowledge of the Lighthouse Point market is unlike anything we've experienced. We couldn't be happier with our life on the Intracoastal." },
  { id:2, name:"James Thornton", loc:"Pompano Beach", stars:5,
    quote:"Gianna staged and sold our home for $185,000 over asking. Her eye for presentation turned what we feared would be a slow sale into an immediate bidding war. Simply outstanding." },
  { id:3, name:"Sofia & Marco DiLorenzo", loc:"Hillsboro Beach", stars:5,
    quote:"Anthony guided us through our first investment property with extraordinary patience and expertise. His understanding of South Florida's investment landscape gave us the confidence to commit. Tremendous returns." }
];

const NEIGHBORHOODS = [
  { name:"Lighthouse Point", tagline:"Where South Florida's Finest Live",
    desc:"A small incorporated city of 11,000 residents, renowned for deep-water canals, private docks, and an intimate community feel. Direct Intracoastal access with no commercial zoning makes it Broward County's most coveted address.",
    medianPrice:"$1.2M", img:"https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=700&h=460&fit=crop&q=80" },
  { name:"Pompano Beach", tagline:"The Rising Crown Jewel",
    desc:"A remarkable transformation driven by a stunning new pier, vibrant dining scene, and accelerating luxury development. Waterfront values continue climbing as savvy buyers arrive ahead of the curve.",
    medianPrice:"$750K", img:"https://images.unsplash.com/photo-1506953823976-52e1fdc0149a?w=700&h=460&fit=crop&q=80" },
  { name:"Hillsboro Beach", tagline:"A Mile of Pure Exclusivity",
    desc:"Occupying just one barrier island mile, Hillsboro Beach is among Florida's most exclusive communities. Entirely residential, gated, and serene — home to some of the most valuable oceanfront estates in the state.",
    medianPrice:"$3.5M", img:"https://images.unsplash.com/photo-1519046904884-53103b34b206?w=700&h=460&fit=crop&q=80" }
];

const CSS = `
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400;1,600&family=Raleway:wght@300;400;500;600;700;800&display=swap');
*,*::before,*::after{box-sizing:border-box;margin:0;padding:0;}
html{scroll-behavior:smooth;}
body{font-family:'Raleway',sans-serif;background:#F5F0E8;color:#0A1628;}
h1,h2,h3,h4{font-family:'Cormorant Garamond',serif;font-weight:500;line-height:1.15;}
::-webkit-scrollbar{width:4px;}::-webkit-scrollbar-track{background:#F5F0E8;}::-webkit-scrollbar-thumb{background:#C9A84C;}
.nav-lnk{color:rgba(255,255,255,.75);font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;cursor:pointer;position:relative;padding-bottom:3px;transition:color .2s;user-select:none;}
.nav-lnk::after{content:'';position:absolute;bottom:0;left:0;width:0;height:1px;background:#C9A84C;transition:width .3s;}
.nav-lnk:hover,.nav-lnk.active{color:#C9A84C;}
.nav-lnk:hover::after,.nav-lnk.active::after{width:100%;}
.btn-g{background:#C9A84C;color:#0A1628;border:none;padding:13px 32px;font-family:'Raleway',sans-serif;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;cursor:pointer;transition:background .2s,transform .15s;display:inline-block;}
.btn-g:hover{background:#9A7B28;transform:translateY(-1px);}
.btn-ow{background:transparent;color:white;border:1px solid rgba(255,255,255,.6);padding:13px 32px;font-family:'Raleway',sans-serif;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;cursor:pointer;transition:all .2s;display:inline-block;}
.btn-ow:hover{background:white;color:#0A1628;}
.btn-od{background:transparent;color:#0A1628;border:1px solid #0A1628;padding:12px 30px;font-family:'Raleway',sans-serif;font-size:10px;font-weight:700;letter-spacing:2.5px;text-transform:uppercase;cursor:pointer;transition:all .2s;display:inline-block;}
.btn-od:hover{background:#0A1628;color:white;}
.lcard{background:white;overflow:hidden;transition:transform .3s,box-shadow .3s;cursor:pointer;}
.lcard:hover{transform:translateY(-7px);box-shadow:0 20px 60px rgba(10,22,40,.15);}
.lcard img{width:100%;height:220px;object-fit:cover;transition:transform .6s;display:block;}
.lcard:hover img{transform:scale(1.05);}
.acard{cursor:pointer;overflow:hidden;position:relative;}
.acard img{width:100%;height:380px;object-fit:cover;transition:transform .6s,filter .4s;filter:grayscale(20%);}
.acard:hover img{transform:scale(1.04);filter:grayscale(0%);}
.ncard{overflow:hidden;cursor:pointer;position:relative;}
.ncard img{width:100%;height:260px;object-fit:cover;transition:transform .6s;display:block;}
.ncard:hover img{transform:scale(1.05);}
.finput{width:100%;background:rgba(255,255,255,.07);border:1px solid rgba(201,168,76,.25);color:white;padding:14px 16px;font-family:'Raleway',sans-serif;font-size:13px;letter-spacing:.3px;outline:none;transition:border-color .2s;margin-bottom:14px;}
.finput:focus{border-color:#C9A84C;}.finput::placeholder{color:rgba(255,255,255,.35);}
.ftab{cursor:pointer;padding:8px 18px;font-size:10px;font-weight:700;letter-spacing:2px;text-transform:uppercase;border:1px solid #DDD8CC;transition:all .2s;background:transparent;font-family:'Raleway',sans-serif;color:#888;}
.ftab.act{border-color:#0A1628;color:#0A1628;background:white;}
.ftab:hover:not(.act){border-color:#C9A84C;color:#C9A84C;}
.fl{font-family:'Raleway',sans-serif;font-size:11px;letter-spacing:1px;cursor:pointer;transition:color .2s;color:rgba(255,255,255,.5);}
.fl:hover{color:#C9A84C;}
.sl{font-family:'Raleway',sans-serif;font-size:10px;font-weight:700;letter-spacing:4px;text-transform:uppercase;color:#C9A84C;}
.gbar{width:48px;height:1px;background:#C9A84C;margin:16px 0;}
.gbarc{width:48px;height:1px;background:#C9A84C;margin:16px auto;}
@keyframes fiu{from{opacity:0;transform:translateY(20px);}to{opacity:1;transform:translateY(0);}}
.fi{opacity:0;animation:fiu .7s ease forwards;}
.d1{animation-delay:.05s;}.d2{animation-delay:.15s;}.d3{animation-delay:.25s;}.d4{animation-delay:.35s;}.d5{animation-delay:.45s;}.d6{animation-delay:.55s;}
.stat-sep:not(:last-child){border-right:1px solid rgba(201,168,76,.2);}
.ni{background:rgba(255,255,255,.07);border:1px solid rgba(201,168,76,.25);color:white;padding:14px 20px;font-family:'Raleway',sans-serif;font-size:13px;outline:none;transition:border-color .2s;flex:1;}
.ni:focus{border-color:#C9A84C;}.ni::placeholder{color:rgba(255,255,255,.35);}
`;

const N = "#0A1628", G = "#C9A84C", IV = "#F5F0E8";

function Star() {
  return <span style={{color:G,fontSize:'14px'}}>★</span>;
}

function Navbar({ page, setPage, scrolled }) {
  const bg = scrolled ? 'rgba(10,22,40,.97)' : 'transparent';
  const bb = scrolled ? '1px solid rgba(201,168,76,.15)' : 'none';
  return (
    <nav style={{position:'sticky',top:0,zIndex:1000,padding:'18px 40px',display:'flex',alignItems:'center',justifyContent:'space-between',background:bg,backdropFilter:scrolled?'blur(8px)':'none',borderBottom:bb,transition:'background .4s,border .4s'}}>
      <div onClick={() => setPage('home')} style={{cursor:'pointer'}}>
        <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'19px',fontWeight:600,letterSpacing:'4px',color:'white',lineHeight:1}}>
          CASILLO <span style={{color:G}}>|</span> SCIORTINO
        </div>
        <div style={{fontSize:'8px',fontWeight:700,letterSpacing:'3.5px',color:'rgba(255,255,255,.4)',textTransform:'uppercase',marginTop:'5px'}}>
          Lighthouse Point · South Florida
        </div>
      </div>
      <div style={{display:'flex',alignItems:'center',gap:'28px'}}>
        {[['home','Home'],['listings','Listings'],['about','About'],['contact','Contact']].map(([k,l]) => (
          <span key={k} className={`nav-lnk ${page===k?'active':''}`} onClick={() => setPage(k)}>{l}</span>
        ))}
        <button className="btn-g" onClick={() => setPage('contact')} style={{padding:'10px 20px',fontSize:'9px'}}>
          Get In Touch
        </button>
      </div>
    </nav>
  );
}

function HeroSection({ setPage }) {
  return (
    <div style={{
      minHeight:'100vh',marginTop:'-64px',
      background:`linear-gradient(to bottom,rgba(10,22,40,.6) 0%,rgba(10,22,40,.3) 45%,rgba(10,22,40,.75) 100%),url('https://images.unsplash.com/photo-1506953823976-52e1fdc0149a?w=1800&q=85') center 40%/cover no-repeat`,
      display:'flex',alignItems:'center',justifyContent:'center',position:'relative',overflow:'hidden'
    }}>
      <div style={{textAlign:'center',padding:'0 20px',maxWidth:'860px'}}>
        <div className="sl fi d1" style={{color:'rgba(201,168,76,.9)',marginBottom:'24px'}}>
          Lighthouse Point · Pompano Beach · Hillsboro Beach
        </div>
        <h1 className="fi d2" style={{fontSize:'clamp(42px,6vw,80px)',color:'white',fontWeight:300,letterSpacing:'2px',lineHeight:1.1,marginBottom:'10px'}}>
          Where Luxury
        </h1>
        <h1 className="fi d2" style={{fontSize:'clamp(42px,6vw,80px)',color:'white',fontWeight:600,letterSpacing:'2px',fontStyle:'italic',lineHeight:1.1,marginBottom:'28px'}}>
          Meets the Waterfront
        </h1>
        <div className="fi d3" style={{width:'60px',height:'1px',background:G,margin:'0 auto 28px'}}/>
        <p className="fi d3" style={{color:'rgba(255,255,255,.75)',fontSize:'15px',fontWeight:400,letterSpacing:'1px',lineHeight:1.8,marginBottom:'44px',maxWidth:'560px',margin:'0 auto 44px'}}>
          South Florida's most trusted team for waterfront estates, luxury residences, and investment-grade properties. Three specialists. One vision. Exceptional results.
        </p>
        <div className="fi d4" style={{display:'flex',gap:'16px',justifyContent:'center',flexWrap:'wrap'}}>
          <button className="btn-g" onClick={() => setPage('listings')}>View Listings</button>
          <button className="btn-ow" onClick={() => setPage('about')}>Meet The Team</button>
        </div>
      </div>
      <div style={{position:'absolute',bottom:'40px',left:'50%',transform:'translateX(-50%)',display:'flex',flexDirection:'column',alignItems:'center',gap:'8px'}}>
        <div style={{width:'1px',height:'40px',background:'rgba(201,168,76,.5)'}}/>
        <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',color:'rgba(255,255,255,.4)',textTransform:'uppercase'}}>Scroll</div>
      </div>
    </div>
  );
}

function StatsBar() {
  const stats = [
    {val:'$480M+',label:'Total Sales Volume'},
    {val:'545+',label:'Homes Sold'},
    {val:'14 Yrs',label:'Market Expertise'},
    {val:'200+',label:'5-Star Reviews'}
  ];
  return (
    <div style={{background:N,borderTop:'1px solid rgba(201,168,76,.2)',borderBottom:'1px solid rgba(201,168,76,.2)'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto',display:'grid',gridTemplateColumns:'repeat(4,1fr)'}}>
        {stats.map((s,i) => (
          <div key={i} className="stat-sep" style={{padding:'32px 20px',textAlign:'center'}}>
            <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'36px',fontWeight:600,color:G,letterSpacing:'1px',lineHeight:1}}>{s.val}</div>
            <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',color:'rgba(255,255,255,.4)',textTransform:'uppercase',marginTop:'8px'}}>{s.label}</div>
          </div>
        ))}
      </div>
    </div>
  );
}

function ListingCard({ l, setPage }) {
  const badgeColor = l.status==='Active' ? '#10B981' : l.status==='Pending' ? '#F59E0B' : '#888';
  return (
    <div className="lcard" onClick={() => setPage('listings')}>
      <div style={{overflow:'hidden',position:'relative'}}>
        <img src={l.img} alt={l.address}/>
        <div style={{position:'absolute',top:'14px',left:'14px',background:badgeColor,color:'white',fontSize:'9px',fontWeight:700,letterSpacing:'2px',textTransform:'uppercase',padding:'5px 11px'}}>
          {l.status}
        </div>
        <div style={{position:'absolute',top:'14px',right:'14px',background:'rgba(10,22,40,.75)',color:'rgba(201,168,76,.9)',fontSize:'9px',fontWeight:700,letterSpacing:'1.5px',textTransform:'uppercase',padding:'5px 11px'}}>
          {l.type}
        </div>
      </div>
      <div style={{padding:'22px 22px 24px'}}>
        <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'26px',fontWeight:600,color:N,letterSpacing:'0.5px',marginBottom:'2px'}}>{l.price}</div>
        <div style={{fontSize:'13px',fontWeight:600,color:'#333',marginBottom:'3px'}}>{l.address}</div>
        <div style={{fontSize:'11px',color:'#888',letterSpacing:'0.5px',marginBottom:'16px'}}>{l.city}</div>
        <div style={{display:'flex',gap:'0',borderTop:'1px solid #F0EBE0',paddingTop:'14px'}}>
          {[`${l.beds} Bed`,`${l.baths} Bath`,`${l.sqft} sqft`].map((d,i) => (
            <div key={i} style={{flex:1,textAlign:'center',borderRight:i<2?'1px solid #F0EBE0':'none',fontSize:'11px',fontWeight:600,color:'#555',letterSpacing:'0.5px'}}>
              {d}
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function FeaturedListings({ setPage }) {
  return (
    <div style={{background:IV,padding:'90px 40px'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto'}}>
        <div style={{display:'flex',alignItems:'flex-end',justifyContent:'space-between',marginBottom:'48px'}}>
          <div>
            <div className="sl">Featured Properties</div>
            <div className="gbar"/>
            <h2 style={{fontSize:'clamp(32px,3.5vw,48px)',color:N,fontWeight:400,lineHeight:1.15}}>
              Exceptional Homes,<br/><em>Exceptional Lives</em>
            </h2>
          </div>
          <button className="btn-od" onClick={() => setPage('listings')} style={{marginBottom:'8px'}}>View All Listings</button>
        </div>
        <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'24px'}}>
          {LISTINGS.slice(0,3).map(l => <ListingCard key={l.id} l={l} setPage={setPage}/>)}
        </div>
      </div>
    </div>
  );
}

function WhySection({ setPage }) {
  const points = [
    {icon:'ti-map-pin',title:'Born Here. Live Here.',body:'All three of our agents are South Florida residents with deep roots in Lighthouse Point and the surrounding communities. We don\'t just sell homes here — we live in them.'},
    {icon:'ti-trophy',title:'Top 1% Producers',body:'Consistently ranked among Broward County\'s top producers, with a combined $480M+ in closed transactions and a track record that speaks for itself.'},
    {icon:'ti-users',title:'A Team, Not an Agent',body:'You get three seasoned professionals collaborating on your behalf — not one agent juggling 30 listings. Every client receives the full weight of our team\'s resources.'},
    {icon:'ti-chart-line',title:'Off-Market Access',body:'Our network gives clients access to properties that never hit the public MLS — a critical advantage in Lighthouse Point\'s competitive waterfront market.'},
  ];
  return (
    <div style={{background:'white',padding:'90px 40px'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto',display:'grid',gridTemplateColumns:'1fr 1fr',gap:'72px',alignItems:'center'}}>
        <div>
          <div className="sl">The Casillo | Sciortino Difference</div>
          <div className="gbar"/>
          <h2 style={{fontSize:'clamp(30px,3.2vw,46px)',color:N,fontWeight:400,lineHeight:1.15,marginBottom:'24px'}}>
            Local Expertise.<br/><em>Exceptional Standards.</em>
          </h2>
          <p style={{fontSize:'14px',lineHeight:1.9,color:'#555',marginBottom:'36px',fontWeight:400}}>
            Lighthouse Point is not just a market to us — it's home. Our team's combined 35+ years of South Florida experience means we understand the nuances of every canal, every neighborhood, and every buyer profile that walks through the door.
          </p>
          <button className="btn-od" onClick={() => setPage('about')}>Meet Our Team</button>
        </div>
        <div style={{display:'grid',gridTemplateColumns:'1fr 1fr',gap:'28px'}}>
          {points.map((p,i) => (
            <div key={i} style={{borderTop:'2px solid '+G,paddingTop:'20px'}}>
              <i className={`ti ${p.icon}`} style={{fontSize:'22px',color:G,marginBottom:'12px',display:'block'}} aria-hidden="true"/>
              <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'18px',fontWeight:600,color:N,marginBottom:'8px',lineHeight:1.2}}>{p.title}</div>
              <p style={{fontSize:'12px',lineHeight:1.7,color:'#666',fontWeight:400}}>{p.body}</p>
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function TeamPreview({ setPage }) {
  return (
    <div style={{background:IV,padding:'90px 40px'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto'}}>
        <div style={{textAlign:'center',marginBottom:'52px'}}>
          <div className="sl">Your South Florida Team</div>
          <div className="gbarc"/>
          <h2 style={{fontSize:'clamp(32px,3.5vw,48px)',color:N,fontWeight:400}}>Meet The Specialists</h2>
        </div>
        <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'28px'}}>
          {AGENTS.map(a => (
            <div key={a.id} className="acard" onClick={() => setPage('about')}>
              <img src={a.img} alt={a.name}/>
              <div style={{position:'absolute',bottom:0,left:0,right:0,background:'linear-gradient(to top,rgba(10,22,40,.95) 0%,transparent 100%)',padding:'48px 24px 24px'}}>
                <div style={{fontSize:'8px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'6px'}}>{a.specialty}</div>
                <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'22px',fontWeight:600,color:'white',marginBottom:'4px'}}>{a.name}</div>
                <div style={{fontSize:'10px',color:'rgba(255,255,255,.55)',letterSpacing:'1px',marginBottom:'12px'}}>{a.title}</div>
                <div style={{width:'32px',height:'1px',background:G}}/>
              </div>
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function TestimonialsSection() {
  return (
    <div style={{background:N,padding:'90px 40px'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto'}}>
        <div style={{textAlign:'center',marginBottom:'52px'}}>
          <div className="sl">What Our Clients Say</div>
          <div className="gbarc"/>
          <h2 style={{fontSize:'clamp(30px,3.2vw,46px)',color:'white',fontWeight:400}}>Words From Our Clients</h2>
        </div>
        <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'24px'}}>
          {TESTIMONIALS.map(t => (
            <div key={t.id} style={{borderLeft:`2px solid ${G}`,padding:'28px 28px 28px 30px',background:'rgba(255,255,255,.05)'}}>
              <div style={{display:'flex',gap:'3px',marginBottom:'18px'}}>
                {[...Array(5)].map((_,i) => <Star key={i}/>)}
              </div>
              <p style={{fontSize:'13px',lineHeight:1.85,color:'rgba(255,255,255,.75)',fontStyle:'italic',marginBottom:'22px',fontFamily:'Cormorant Garamond,serif',fontWeight:300,letterSpacing:'0.3px'}}>
                "{t.quote}"
              </p>
              <div style={{fontSize:'12px',fontWeight:700,color:'white',letterSpacing:'1px'}}>{t.name}</div>
              <div style={{fontSize:'10px',color:G,letterSpacing:'1.5px',marginTop:'3px'}}>{t.loc}</div>
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function NeighborhoodsSection({ setPage }) {
  return (
    <div style={{background:'white',padding:'90px 40px'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto'}}>
        <div style={{textAlign:'center',marginBottom:'52px'}}>
          <div className="sl">Our Markets</div>
          <div className="gbarc"/>
          <h2 style={{fontSize:'clamp(30px,3.2vw,46px)',color:N,fontWeight:400}}>Neighborhoods We Call Home</h2>
        </div>
        <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'24px'}}>
          {NEIGHBORHOODS.map((n,i) => (
            <div key={i} className="ncard" onClick={() => setPage('listings')}>
              <div style={{overflow:'hidden',position:'relative'}}>
                <img src={n.img} alt={n.name}/>
                <div style={{position:'absolute',inset:0,background:'linear-gradient(to top,rgba(10,22,40,.85) 0%,transparent 55%)'}}/>
                <div style={{position:'absolute',bottom:'22px',left:'22px',right:'22px'}}>
                  <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'5px'}}>Median: {n.medianPrice}</div>
                  <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'22px',fontWeight:600,color:'white',marginBottom:'3px'}}>{n.name}</div>
                  <div style={{fontSize:'10px',color:'rgba(255,255,255,.6)',letterSpacing:'0.5px',fontStyle:'italic'}}>{n.tagline}</div>
                </div>
              </div>
              <div style={{padding:'20px 20px 22px',borderBottom:`2px solid ${G}`,borderLeft:'1px solid #EDE7DA',borderRight:'1px solid #EDE7DA'}}>
                <p style={{fontSize:'12px',lineHeight:1.75,color:'#666'}}>{n.desc}</p>
              </div>
            </div>
          ))}
        </div>
      </div>
    </div>
  );
}

function CTASection({ setPage }) {
  const [email, setEmail] = useState('');
  return (
    <div style={{background:N,padding:'80px 40px',borderTop:'1px solid rgba(201,168,76,.15)'}}>
      <div style={{maxWidth:'640px',margin:'0 auto',textAlign:'center'}}>
        <div className="sl">Stay Ahead of the Market</div>
        <div className="gbarc"/>
        <h2 style={{fontSize:'clamp(28px,3vw,42px)',color:'white',fontWeight:400,marginBottom:'16px'}}>
          Get the <em>Lighthouse Point</em> Market Report
        </h2>
        <p style={{fontSize:'13px',color:'rgba(255,255,255,.55)',letterSpacing:'0.5px',lineHeight:1.8,marginBottom:'36px'}}>
          Monthly insights on waterfront sales, new listings, price trends, and investment opportunities — delivered directly to your inbox.
        </p>
        <div style={{display:'flex',gap:'0'}}>
          <input className="ni" placeholder="Your email address" value={email} onChange={e => setEmail(e.target.value)}/>
          <button className="btn-g" style={{whiteSpace:'nowrap',borderRadius:0}} onClick={() => setEmail('')}>
            Subscribe
          </button>
        </div>
        <p style={{fontSize:'10px',color:'rgba(255,255,255,.25)',marginTop:'12px',letterSpacing:'0.5px'}}>
          No spam. Unsubscribe anytime.
        </p>
      </div>
    </div>
  );
}

function HomePage({ setPage }) {
  return (
    <>
      <HeroSection setPage={setPage}/>
      <StatsBar/>
      <FeaturedListings setPage={setPage}/>
      <WhySection setPage={setPage}/>
      <TeamPreview setPage={setPage}/>
      <TestimonialsSection/>
      <NeighborhoodsSection setPage={setPage}/>
      <CTASection setPage={setPage}/>
    </>
  );
}

function AboutPage({ setPage }) {
  return (
    <>
      <div style={{background:`linear-gradient(to right,rgba(10,22,40,.92),rgba(10,22,40,.8)),url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e?w=1400&q=80') center/cover`,padding:'140px 40px 80px',marginTop:'-64px'}}>
        <div style={{maxWidth:'700px',margin:'0 auto',textAlign:'center'}}>
          <div className="sl fi d1">About Our Team</div>
          <div className="gbarc"/>
          <h1 className="fi d2" style={{fontSize:'clamp(36px,5vw,64px)',color:'white',fontWeight:400,lineHeight:1.1,marginBottom:'20px'}}>
            Three Specialists.<br/><em>One Vision.</em>
          </h1>
          <p className="fi d3" style={{fontSize:'14px',color:'rgba(255,255,255,.65)',lineHeight:1.8,letterSpacing:'0.3px'}}>
            Casillo | Sciortino brings together three of South Florida's most accomplished real estate professionals, united by a shared commitment to exceptional client service and deep market expertise.
          </p>
        </div>
      </div>

      <div style={{background:IV,padding:'80px 40px'}}>
        <div style={{maxWidth:'1100px',margin:'0 auto'}}>
          <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'32px',marginBottom:'80px'}}>
            {AGENTS.map(a => (
              <div key={a.id} style={{background:'white',overflow:'hidden'}}>
                <div style={{overflow:'hidden',position:'relative'}}>
                  <img src={a.img} alt={a.name} style={{width:'100%',height:'320px',objectFit:'cover',display:'block',filter:'grayscale(10%)'}}/>
                  <div style={{position:'absolute',bottom:0,left:0,right:0,background:'linear-gradient(to top,rgba(10,22,40,.85),transparent)',padding:'36px 24px 20px'}}>
                    <div style={{fontSize:'8px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'4px'}}>{a.specialty}</div>
                    <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'22px',fontWeight:600,color:'white'}}>{a.name}</div>
                  </div>
                </div>
                <div style={{padding:'24px'}}>
                  <div style={{fontSize:'10px',color:'#888',letterSpacing:'1.5px',marginBottom:'12px',fontWeight:600}}>{a.license}</div>
                  <p style={{fontSize:'12.5px',lineHeight:1.8,color:'#555',marginBottom:'20px'}}>{a.bio}</p>
                  <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'4px',marginBottom:'20px'}}>
                    {[['Transactions',a.stats.deals],['Volume',a.stats.volume],['Experience',a.stats.years+' yrs']].map(([k,v]) => (
                      <div key={k} style={{background:IV,padding:'12px 8px',textAlign:'center'}}>
                        <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'18px',fontWeight:600,color:N,lineHeight:1}}>{v}</div>
                        <div style={{fontSize:'8px',fontWeight:700,letterSpacing:'1.5px',textTransform:'uppercase',color:'#888',marginTop:'4px'}}>{k}</div>
                      </div>
                    ))}
                  </div>
                  <div style={{display:'flex',flexDirection:'column',gap:'8px'}}>
                    <div style={{display:'flex',alignItems:'center',gap:'8px'}}>
                      <i className="ti ti-phone" style={{fontSize:'13px',color:G}} aria-hidden="true"/>
                      <span style={{fontSize:'12px',color:'#555'}}>{a.phone}</span>
                    </div>
                    <div style={{display:'flex',alignItems:'center',gap:'8px'}}>
                      <i className="ti ti-mail" style={{fontSize:'13px',color:G}} aria-hidden="true"/>
                      <span style={{fontSize:'12px',color:'#555'}}>{a.email}</span>
                    </div>
                  </div>
                </div>
              </div>
            ))}
          </div>

          <div style={{background:N,padding:'56px',textAlign:'center',borderTop:`3px solid ${G}`}}>
            <div className="sl" style={{color:G,marginBottom:'16px'}}>Our Commitment</div>
            <h2 style={{fontFamily:'Cormorant Garamond,serif',fontSize:'clamp(26px,3vw,40px)',color:'white',fontWeight:300,lineHeight:1.4,maxWidth:'700px',margin:'0 auto 28px',fontStyle:'italic'}}>
              "We don't measure success by transactions closed. We measure it by lives changed, dreams realized, and relationships built that last a lifetime."
            </h2>
            <div style={{width:'48px',height:'1px',background:G,margin:'0 auto 28px'}}/>
            <button className="btn-g" onClick={() => setPage('contact')}>Work With Us</button>
          </div>
        </div>
      </div>
    </>
  );
}

function ListingsPage({ setPage }) {
  const [filter, setFilter] = useState('All');
  const filters = ['All','Active','Pending','Sold'];
  const shown = filter === 'All' ? LISTINGS : LISTINGS.filter(l => l.status === filter);
  return (
    <>
      <div style={{background:`linear-gradient(to right,rgba(10,22,40,.9),rgba(10,22,40,.75)),url('https://images.unsplash.com/photo-1600596542815-ffad4c1539a9?w=1400&q=80') center/cover`,padding:'130px 40px 60px',marginTop:'-64px'}}>
        <div style={{maxWidth:'1100px',margin:'0 auto'}}>
          <div className="sl fi d1" style={{marginBottom:'12px'}}>Our Portfolio</div>
          <div className="gbar"/>
          <h1 className="fi d2" style={{fontSize:'clamp(34px,4.5vw,60px)',color:'white',fontWeight:400,lineHeight:1.1}}>
            South Florida<br/><em>Luxury Listings</em>
          </h1>
        </div>
      </div>

      <div style={{background:IV,padding:'48px 40px 80px'}}>
        <div style={{maxWidth:'1100px',margin:'0 auto'}}>
          <div style={{display:'flex',alignItems:'center',justifyContent:'space-between',marginBottom:'36px'}}>
            <div style={{display:'flex',gap:'8px'}}>
              {filters.map(f => (
                <button key={f} className={`ftab ${filter===f?'act':''}`} onClick={() => setFilter(f)}>{f}</button>
              ))}
            </div>
            <div style={{fontSize:'11px',color:'#888',letterSpacing:'1px'}}>
              {shown.length} propert{shown.length===1?'y':'ies'} found
            </div>
          </div>
          <div style={{display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'24px'}}>
            {shown.map(l => <ListingCard key={l.id} l={l} setPage={setPage}/>)}
          </div>
          {shown.length === 0 && (
            <div style={{textAlign:'center',padding:'60px',color:'#888',fontSize:'14px'}}>No listings match this filter.</div>
          )}
          <div style={{background:N,padding:'48px',marginTop:'60px',display:'flex',alignItems:'center',justifyContent:'space-between',gap:'40px'}}>
            <div>
              <div className="sl" style={{color:G,marginBottom:'8px'}}>Don't see what you're looking for?</div>
              <h3 style={{fontFamily:'Cormorant Garamond,serif',fontSize:'24px',fontWeight:400,color:'white',lineHeight:1.3}}>
                We have access to off-market properties<br/><em>not listed here.</em>
              </h3>
            </div>
            <button className="btn-g" onClick={() => setPage('contact')} style={{whiteSpace:'nowrap'}}>Contact Our Team</button>
          </div>
        </div>
      </div>
    </>
  );
}

function ContactPage() {
  const [form, setForm] = useState({name:'',email:'',phone:'',intent:'buying',message:''});
  const set = (k) => (e) => setForm(f => ({...f,[k]:e.target.value}));
  return (
    <>
      <div style={{background:N,paddingTop:'130px',paddingBottom:'0',marginTop:'-64px'}}>
        <div style={{maxWidth:'1100px',margin:'0 auto',padding:'0 40px 80px',display:'grid',gridTemplateColumns:'1fr 1.1fr',gap:'72px',alignItems:'start'}}>
          <div>
            <div className="sl fi d1" style={{color:G,marginBottom:'12px'}}>Get In Touch</div>
            <div style={{width:'48px',height:'1px',background:G,margin:'0 0 24px'}}/>
            <h1 className="fi d2" style={{fontSize:'clamp(34px,4vw,54px)',color:'white',fontWeight:400,lineHeight:1.1,marginBottom:'24px'}}>
              Let's Find Your<br/><em>Perfect Property</em>
            </h1>
            <p className="fi d3" style={{fontSize:'13px',color:'rgba(255,255,255,.55)',lineHeight:1.85,marginBottom:'48px'}}>
              Whether you're buying your dream waterfront home, selling a prized asset, or exploring South Florida investment opportunities — our team is ready to guide you.
            </p>
            <div style={{display:'flex',flexDirection:'column',gap:'24px'}}>
              {AGENTS.map(a => (
                <div key={a.id} style={{display:'flex',gap:'16px',alignItems:'center',borderLeft:`2px solid ${G}`,paddingLeft:'16px'}}>
                  <img src={a.img} alt={a.name} style={{width:'52px',height:'52px',objectFit:'cover',objectPosition:'top',borderRadius:'50%',filter:'grayscale(10%)'}}/>
                  <div>
                    <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'17px',fontWeight:600,color:'white',lineHeight:1.1}}>{a.name}</div>
                    <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'2px',color:G,textTransform:'uppercase',marginTop:'3px'}}>{a.specialty}</div>
                    <div style={{fontSize:'11px',color:'rgba(255,255,255,.4)',marginTop:'3px'}}>{a.phone}</div>
                  </div>
                </div>
              ))}
            </div>
          </div>

          <div style={{background:'rgba(255,255,255,.04)',border:'1px solid rgba(201,168,76,.15)',padding:'40px'}}>
            <h3 style={{fontFamily:'Cormorant Garamond,serif',fontSize:'26px',fontWeight:500,color:'white',marginBottom:'28px'}}>Send Us a Message</h3>
            <div style={{display:'grid',gridTemplateColumns:'1fr 1fr',gap:'0 14px'}}>
              <input className="finput" placeholder="Full Name" value={form.name} onChange={set('name')}/>
              <input className="finput" placeholder="Email Address" value={form.email} onChange={set('email')}/>
            </div>
            <input className="finput" placeholder="Phone Number" value={form.phone} onChange={set('phone')}/>
            <select className="finput" value={form.intent} onChange={set('intent')} style={{appearance:'none',cursor:'pointer'}}>
              <option value="buying">I'm looking to Buy</option>
              <option value="selling">I'm looking to Sell</option>
              <option value="invest">Investment Inquiry</option>
              <option value="valuation">Home Valuation</option>
              <option value="other">General Inquiry</option>
            </select>
            <textarea className="finput" placeholder="Tell us about your ideal property or how we can help..." value={form.message} onChange={set('message')} style={{height:'110px',resize:'vertical'}}/>
            <button className="btn-g" style={{width:'100%',padding:'16px',fontSize:'11px'}}
              onClick={() => setForm({name:'',email:'',phone:'',intent:'buying',message:''})}>
              Send Message
            </button>
            <p style={{fontSize:'10px',color:'rgba(255,255,255,.25)',textAlign:'center',marginTop:'12px',letterSpacing:'0.5px'}}>
              We respond to all inquiries within 24 hours.
            </p>
          </div>
        </div>
      </div>

      <div style={{background:'rgba(10,22,40,.97)',padding:'52px 40px',borderTop:'1px solid rgba(201,168,76,.1)'}}>
        <div style={{maxWidth:'1100px',margin:'0 auto',display:'grid',gridTemplateColumns:'repeat(3,1fr)',gap:'40px',textAlign:'center'}}>
          {[
            {icon:'ti-map-pin',label:'Office Location',val:'Lighthouse Point, FL 33064'},
            {icon:'ti-phone',label:'Main Line',val:'(954) 555-0100'},
            {icon:'ti-clock',label:'Hours',val:'Mon–Sat 8am–7pm · Sun 10am–5pm'}
          ].map((item,i) => (
            <div key={i}>
              <i className={`ti ${item.icon}`} style={{fontSize:'24px',color:G,marginBottom:'12px',display:'block'}} aria-hidden="true"/>
              <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:'rgba(255,255,255,.35)',marginBottom:'6px'}}>{item.label}</div>
              <div style={{fontSize:'13px',color:'rgba(255,255,255,.7)',fontWeight:500}}>{item.val}</div>
            </div>
          ))}
        </div>
      </div>
    </>
  );
}

function Footer({ page, setPage }) {
  return (
    <footer style={{background:'#060E1A',padding:'60px 40px 32px',borderTop:'1px solid rgba(201,168,76,.15)'}}>
      <div style={{maxWidth:'1100px',margin:'0 auto'}}>
        <div style={{display:'grid',gridTemplateColumns:'2fr 1fr 1fr 1fr',gap:'48px',marginBottom:'48px'}}>
          <div>
            <div style={{fontFamily:'Cormorant Garamond,serif',fontSize:'18px',fontWeight:600,letterSpacing:'4px',color:'white',marginBottom:'6px'}}>
              CASILLO <span style={{color:G}}>|</span> SCIORTINO
            </div>
            <div style={{fontSize:'8px',fontWeight:700,letterSpacing:'3px',color:'rgba(255,255,255,.35)',textTransform:'uppercase',marginBottom:'18px'}}>
              Lighthouse Point · South Florida
            </div>
            <p style={{fontSize:'12px',color:'rgba(255,255,255,.4)',lineHeight:1.8,maxWidth:'280px'}}>
              South Florida's most trusted team for waterfront estates and luxury residences. Three specialists, one vision, exceptional results.
            </p>
            <div style={{display:'flex',gap:'14px',marginTop:'24px'}}>
              {['ti-brand-instagram','ti-brand-facebook','ti-brand-linkedin'].map(ic => (
                <div key={ic} style={{width:'36px',height:'36px',border:'1px solid rgba(201,168,76,.25)',display:'flex',alignItems:'center',justifyContent:'center',cursor:'pointer',transition:'border-color .2s'}}>
                  <i className={`ti ${ic}`} style={{fontSize:'15px',color:'rgba(255,255,255,.5)'}} aria-hidden="true"/>
                </div>
              ))}
            </div>
          </div>
          <div>
            <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'18px'}}>Navigation</div>
            {[['home','Home'],['listings','Listings'],['about','About'],['contact','Contact']].map(([k,l]) => (
              <div key={k} style={{marginBottom:'10px'}}>
                <span className="fl" onClick={() => setPage(k)}>{l}</span>
              </div>
            ))}
          </div>
          <div>
            <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'18px'}}>Communities</div>
            {['Lighthouse Point','Pompano Beach','Hillsboro Beach','Deerfield Beach','Boca Raton'].map(n => (
              <div key={n} style={{marginBottom:'10px'}}>
                <span className="fl" onClick={() => setPage('listings')}>{n}</span>
              </div>
            ))}
          </div>
          <div>
            <div style={{fontSize:'9px',fontWeight:700,letterSpacing:'3px',textTransform:'uppercase',color:G,marginBottom:'18px'}}>Contact</div>
            {['(954) 555-0100','info@casillosciortino.com','Lighthouse Point, FL 33064'].map((c,i) => (
              <div key={i} style={{marginBottom:'10px',fontSize:'11px',color:'rgba(255,255,255,.45)',letterSpacing:'0.3px'}}>{c}</div>
            ))}
            <div style={{marginTop:'20px'}}>
              <button className="btn-g" onClick={() => setPage('contact')} style={{padding:'11px 22px',fontSize:'9px'}}>
                Get In Touch
              </button>
            </div>
          </div>
        </div>
        <div style={{borderTop:'1px solid rgba(255,255,255,.07)',paddingTop:'24px',display:'flex',justifyContent:'space-between',alignItems:'center'}}>
          <div style={{fontSize:'10px',color:'rgba(255,255,255,.2)',letterSpacing:'0.5px'}}>
            © 2025 Casillo | Sciortino Real Estate. All rights reserved. Licensed in the State of Florida.
          </div>
          <div style={{display:'flex',gap:'24px'}}>
            {['Privacy Policy','Terms of Service','Fair Housing'].map(l => (
              <span key={l} style={{fontSize:'10px',color:'rgba(255,255,255,.2)',cursor:'pointer',letterSpacing:'0.3px'}}>{l}</span>
            ))}
          </div>
        </div>
      </div>
    </footer>
  );
}

export default function App() {
  const [page, setPage] = useState('home');
  const [scrollY, setScrollY] = useState(0);

  useEffect(() => {
    const s = document.createElement('style');
    s.id = 'cs-global';
    s.textContent = CSS;
    document.head.appendChild(s);
    return () => document.getElementById('cs-global')?.remove();
  }, []);

  useEffect(() => {
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }, [page]);

  useEffect(() => {
    const fn = () => setScrollY(window.scrollY);
    window.addEventListener('scroll', fn, { passive: true });
    return () => window.removeEventListener('scroll', fn);
  }, []);

  const navigate = (p) => { setPage(p); };

  return (
    <div style={{ fontFamily: 'Raleway,sans-serif', background: IV, minHeight: '100vh', overflowX: 'hidden' }}>
      <Navbar page={page} setPage={navigate} scrolled={scrollY > 50} />
      {page === 'home'     && <HomePage     setPage={navigate} />}
      {page === 'about'    && <AboutPage    setPage={navigate} />}
      {page === 'listings' && <ListingsPage setPage={navigate} />}
      {page === 'contact'  && <ContactPage  setPage={navigate} />}
      <Footer page={page} setPage={navigate} />
    </div>
  );
}
