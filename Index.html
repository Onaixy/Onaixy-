# Core setup 
All in one ai tools website. 

# React project banaiye
npx create-react-app onaixy-core-setup

cd onaixy-core-setup

# Firebase install karein
npm install firebase

# GitHub Pages deploy package install karein
npm install gh-pages --save-dev

{
  "homepage": "https://USERNAME.github.io/onaixy-core-setup",
  "scripts": {
    "start": "react-scripts start",
    "build": "react-scripts build",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d build"
  }
}

import { initializeApp } from "firebase/app";
import { getFirestore } from "firebase/firestore";
import { getAuth } from "firebase/auth";

const firebaseConfig = {
  apiKey: "YOUR-API-KEY",
  authDomain: "YOUR-PROJECT.firebaseapp.com",
  projectId: "YOUR-PROJECT-ID",
  storageBucket: "YOUR-PROJECT.appspot.com",
  messagingSenderId: "YOUR-SENDER-ID",
  appId: "YOUR-APP-ID"
};

const app = initializeApp(firebaseConfig);
export const db = getFirestore(app);
export const auth = getAuth(app);

import React from "react";
import { auth } from "./firebase";

function App() {
  return (
    <div style={{ textAlign: "center", marginTop: "50px" }}>
      <h1>Onaixy.com Live Test</h1>
      <p>React + Firebase + GitHub Pages</p>
    </div>
  );
}

export default App;

# Git init karein
git init
git remote add origin https://github.com/USERNAME/onaixy-core-setup.git
git add .
git commit -m "Initial Commit"
git push -u origin main

# Deploy karein
npm run deploy
{
  "name": "onaixy-live",
  "private": true,
  "version": "1.0.0",
  "type": "module",
  "scripts": {
    "dev": "vite",
    "build": "vite build",
    "preview": "vite preview --port 5173",
    "predeploy": "npm run build",
    "deploy": "gh-pages -d dist"
  },
  "dependencies": {
    "firebase": "^10.12.5",
    "react": "^18.2.0",
    "react-dom": "^18.2.0",
    "react-router-dom": "^6.23.1"
  },
  "devDependencies": {
    "gh-pages": "^6.0.0",
    "vite": "^5.3.1"
  }
}
import { defineConfig } from 'vite'
import react from '@vitejs/plugin-react'

// Replace REPO_NAME below with your GitHub repo name
export default defineConfig({
  plugins: [react()],
  base: '/REPO_NAME/'
})
<!doctype html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Onaixy</title>
    <meta name="description" content="Onaixy — Simple Launch" />
    <link rel="icon" href="/REPO_NAME/favicon.ico" />
  </head>
  <body>
    <div id="root"></div>
    <script type="module" src="/REPO_NAME/src/main.jsx"></script>
  </body>
</html>
node_modules
.DS_Store
.env
.dist
VITE_FB_API_KEY=YOUR_API_KEY
VITE_FB_AUTH_DOMAIN=YOUR_PROJECT.firebaseapp.com
VITE_FB_PROJECT_ID=YOUR_PROJECT_ID
VITE_FB_STORAGE=YOUR_PROJECT.appspot.com
VITE_FB_MSG=YOUR_SENDER_ID
VITE_FB_APP_ID=YOUR_APP_ID
import { initializeApp } from 'firebase/app'
import { getAuth, GoogleAuthProvider } from 'firebase/auth'
import { getFirestore } from 'firebase/firestore'

const firebaseConfig = {
  apiKey: import.meta.env.VITE_FB_API_KEY,
  authDomain: import.meta.env.VITE_FB_AUTH_DOMAIN,
  projectId: import.meta.env.VITE_FB_PROJECT_ID,
  storageBucket: import.meta.env.VITE_FB_STORAGE,
  messagingSenderId: import.meta.env.VITE_FB_MSG,
  appId: import.meta.env.VITE_FB_APP_ID
}

const app = initializeApp(firebaseConfig)
export const auth = getAuth(app)
export const googleProvider = new GoogleAuthProvider()
export const db = getFirestore(app)
import React from 'react'
import ReactDOM from 'react-dom/client'
import { BrowserRouter } from 'react-router-dom'
import App from './App.jsx'
import './styles/global.css'

ReactDOM.createRoot(document.getElementById('root')).render(
  <React.StrictMode>
    <BrowserRouter basename={import.meta.env.BASE_URL}>
      <App />
    </BrowserRouter>
  </React.StrictMode>
)
import { Routes, Route } from 'react-router-dom'
import Navbar from './components/Navbar.jsx'
import Footer from './components/Footer.jsx'
import Home from './pages/Home.jsx'
import About from './pages/About.jsx'
import Contact from './pages/Contact.jsx'
import Login from './pages/Login.jsx'
import Dashboard from './pages/Dashboard.jsx'
import AIChat from './pages/AIChat.jsx'
import ProtectedRoute from './components/ProtectedRoute.jsx'

export default function App(){
  return (
    <div className="min-h-screen flex flex-col">
      <Navbar />
      <main style={{flex: 1, padding: '24px 16px', maxWidth: 980, margin: '0 auto'}}>
        <Routes>
          <Route path="/" element={<Home />} />
          <Route path="/about" element={<About />} />
          <Route path="/contact" element={<Contact />} />
          <Route path="/login" element={<Login />} />
          <Route path="/dashboard" element={
            <ProtectedRoute>
              <Dashboard />
            </ProtectedRoute>
          } />
          <Route path="/ai" element={<AIChat />} />
        </Routes>
      </main>
      <Footer />
    </div>
  )
}
import { Link, NavLink } from 'react-router-dom'

const linkStyle = ({isActive}) => ({
  padding: '8px 12px',
  borderRadius: 8,
  textDecoration: 'none',
  color: isActive ? '#fff' : '#222',
  background: isActive ? '#6d28d9' : 'transparent'
})

export default function Navbar(){
  return (
    <header style={{borderBottom: '1px solid #eee'}}>
      <nav style={{display: 'flex', gap: 12, alignItems: 'center', padding: '12px 16px', maxWidth: 980, margin: '0 auto'}}>
        <Link to="/" style={{fontWeight: 800, fontSize: 18}}>Onaixy</Link>
        <div style={{display: 'flex', gap: 8}}>
          <NavLink to="/" style={linkStyle}>Home</NavLink>
          <NavLink to="/about" style={linkStyle}>About</NavLink>
          <NavLink to="/contact" style={linkStyle}>Contact</NavLink>
          <NavLink to="/ai" style={linkStyle}>AI Chat</NavLink>
          <NavLink to="/dashboard" style={linkStyle}>Dashboard</NavLink>
          <NavLink to="/login" style={linkStyle}>Login</NavLink>
        </div>
      </nav>
    </header>
  )
}
export default function Footer(){
  return (
    <footer style={{borderTop: '1px solid #eee', padding: '16px'}}>
      <div style={{maxWidth: 980, margin: '0 auto', display: 'flex', justifyContent: 'space-between'}}>
        <span>© {new Date().getFullYear()} Onaixy</span>
        <a href="https://github.com/USERNAME/REPO_NAME" target="_blank" rel="noreferrer">GitHub</a>
      </div>
    </footer>
  )
}
import { useEffect } from 'react'
import { useNavigate } from 'react-router-dom'
import { auth } from '../firebase'

export default function ProtectedRoute({ children }){
  const navigate = useNavigate()
  useEffect(() => {
    const unsub = auth.onAuthStateChanged((u)=>{
      if(!u) navigate('/login')
    })
    return () => unsub()
  }, [navigate])
  return children
}
import { Link } from 'react-router-dom'
export default function Home(){
  return (
    <section>
      <h1>Welcome to Onaixy</h1>
      <p>Simple launch on GitHub Pages + Firebase backend.</p>
      <div style={{display:'flex', gap:12, marginTop:16}}>
        <Link to="/ai">Try AI Chat</Link>
        <Link to="/login">Login</Link>
      </div>
    </section>
  )
}
export default function About(){
  return (
    <section>
      <h2>About Onaixy</h2>
      <p>Lightweight MVP running on free/low-cost infra. Upgrade anytime.</p>
    </section>
  )
}
import { useState } from 'react'
import { db } from '../firebase'
import { collection, addDoc, serverTimestamp } from 'firebase/firestore'

export default function Contact(){
  const [form, setForm] = useState({name:'', email:'', message:''})
  const [status, setStatus] = useState('')

  const onSubmit = async (e)=>{
    e.preventDefault()
    setStatus('Saving...')
    try{
      await addDoc(collection(db,'contacts'),{
        ...form,
        createdAt: serverTimestamp()
      })
      setStatus('Thanks! We will get back to you.')
      setForm({name:'', email:'', message:''})
    }catch(err){
      setStatus('Error: '+err.message)
    }
  }

  return (
    <section>
      <h2>Contact</h2>
      <form onSubmit={onSubmit} style={{display:'grid', gap:12, maxWidth:480}}>
        <input placeholder="Name" value={form.name} onChange={e=>setForm({...form, name:e.target.value})} required/>
        <input placeholder="Email" type="email" value={form.email} onChange={e=>setForm({...form, email:e.target.value})} required/>
        <textarea placeholder="Message" rows={5} value={form.message} onChange={e=>setForm({...form, message:e.target.value})} required/>
        <button type="submit">Send</button>
      </form>
      <p style={{marginTop:8}}>{status}</p>
    </section>
  )
}
import { useEffect, useState } from 'react'
import { auth, googleProvider } from '../firebase'
import { signInWithEmailAndPassword, signInWithPopup, createUserWithEmailAndPassword, signOut } from 'firebase/auth'

export default function Login(){
  const [email, setEmail] = useState('')
  const [pass, setPass] = useState('')
  const [user, setUser] = useState(null)
  const [msg, setMsg] = useState('')

  useEffect(()=>{
    const unsub = auth.onAuthStateChanged(setUser)
    return () => unsub()
  },[])

  const signin = async(e)=>{
    e.preventDefault()
    try{ await signInWithEmailAndPassword(auth, email, pass); setMsg('Signed in!') }catch(err){ setMsg(err.message) }
  }
  const signup = async()=>{
    try{ await createUserWithEmailAndPassword(auth, email, pass); setMsg('Account created!') }catch(err){ setMsg(err.message) }
  }
  const google = async()=>{
    try{ await signInWithPopup(auth, googleProvider); setMsg('Google sign-in ok') }catch(err){ setMsg(err.message) }
  }
  const logout = async()=>{ await signOut(auth) }

  return (
    <section>
      <h2>{user? 'Account' : 'Login / Sign up'}</h2>
      {user? (
        <>
          <p>Logged in as <b>{user.email || user.displayName}</b></p>
          <button onClick={logout}>Sign out</button>
        </>
      ):(
        <form onSubmit={signin} style={{display:'grid', gap:10, maxWidth:360}}>
          <input placeholder="Email" value={email} onChange={e=>setEmail(e.target.value)} type="email" required />
          <input placeholder="Password" value={pass} onChange={e=>setPass(e.target.value)} type="password" required />
          <button type="submit">Sign in</button>
          <button type="button" onClick={signup}>Create account</button>
          <button type="button" onClick={google}>Continue with Google</button>
        </form>
      )}
      <p style={{marginTop:8}}>{msg}</p>
    </section>
  )
}
import { useEffect, useState } from 'react'
import { auth } from '../firebase'

export default function Dashboard(){
  const [user, setUser] = useState(null)
  useEffect(()=>{ const u = auth.currentUser; setUser(u) },[])
  return (
    <section>
      <h2>Dashboard</h2>
      <p>Welcome {user?.email || user?.displayName || 'Guest'}!</p>
      <ul>
        <li>✓ Private page (auth required)</li>
        <li>✓ Ready for adding Ads / Pro features</li>
        <li>✓ Minimal analytics-ready layout</li>
      </ul>
    </section>
  )
}
import { useState } from 'react'

export default function AIChat(){
  const [input, setInput] = useState('')
  const [messages, setMessages] = useState([{role:'system', content:'Say hi to Onaixy!'}])

  const send = async()=>{
    if(!input.trim()) return
    // Placeholder: in production call your AI API via serverless function
    const reply = `You said: ${input}`
    setMessages(m=>[...m,{role:'user', content: input},{role:'assistant', content: reply}])
    setInput('')
  }

  return (
    <section>
      <h2>AI Chat (Demo)</h2>
      <div style={{display:'grid', gap:8, maxWidth:600}}>
        <div style={{border:'1px solid #eee', borderRadius:8, padding:12, minHeight:160}}>
          {messages.map((m,i)=> (
            <div key={i} style={{margin:'6px 0'}}>
              <b>{m.role}:</b> {m.content}
            </div>
          ))}
        </div>
        <div style={{display:'flex', gap:8}}>
          <input value={input} onChange={e=>setInput(e.target.value)} placeholder="Type here..." style={{flex:1}}/>
          <button onClick={send}>Send</button>
        </div>
      </div>
    </section>
  )
}
*{box-sizing:border-box}
body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Helvetica,Arial,sans-serif;color:#222}
a{color:#6d28d9}
button{padding:8px 12px;border:1px solid #ddd;border-radius:8px;background:#fafafa;cursor:pointer}
input,textarea{padding:10px;border:1px solid #ddd;border-radius:8px}
h1,h2{margin:8px 0}
# Onaixy — Live on GitHub Pages (Vite + React + Firebase)

## Setup
1) Install deps
```bash
npm i
npm run dev
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO_NAME.git
git push -u origin main

npm run deploy
https://USERNAME.github.io/REPO_NAME/
npm i
git init
git add .
git commit -m "init"
git branch -M main
git remote add origin https://github.com/USERNAME/REPO_NAME.git
git push -u origin main
npm run deploy
