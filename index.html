import { useState, useEffect, useCallback } from "react";

// ─── ICONS ───────────────────────────────────────────────────────────────────
const Icon = ({ name, size = 20 }) => {
  const icons = {
    home: "M3 9l9-7 9 7v11a2 2 0 01-2 2H5a2 2 0 01-2-2z M9 22V12h6v10",
    users: "M17 21v-2a4 4 0 00-4-4H5a4 4 0 00-4 4v2 M23 21v-2a4 4 0 00-3-3.87 M16 3.13a4 4 0 010 7.75",
    calendar: "M8 2v4 M16 2v4 M3 10h18 M5 4h14a2 2 0 012 2v14a2 2 0 01-2 2H5a2 2 0 01-2-2V6a2 2 0 012-2z",
    bell: "M18 8A6 6 0 006 8c0 7-3 9-3 9h18s-3-2-3-9 M13.73 21a2 2 0 01-3.46 0",
    shopping: "M6 2L3 6v14a2 2 0 002 2h14a2 2 0 002-2V6l-3-4z M3 6h18 M16 10a4 4 0 01-8 0",
    ruler: "M21.3 8.7l-8-8a1 1 0 00-1.4 0l-10 10 1.4 1.4 1.3-1.3 2.8 2.8-1.3 1.3 1.4 1.4 1.3-1.3 2.8 2.8-1.3 1.3 1.4 1.4 1.3-1.3 2.8 2.8-1.3 1.3 1.4 1.4 8.6-8.6a1 1 0 000-1.4z",
    check: "M20 6L9 17l-5-5",
    plus: "M12 5v14 M5 12h14",
    trash: "M3 6h18 M19 6l-1 14H6L5 6 M8 6V4h8v2",
    edit: "M11 4H4a2 2 0 00-2 2v14a2 2 0 002 2h14a2 2 0 002-2v-7 M18.5 2.5a2.12 2.12 0 013 3L12 15l-4 1 1-4 9.5-9.5z",
    x: "M18 6L6 18 M6 6l12 12",
    star: "M12 2l3.09 6.26L22 9.27l-5 4.87 1.18 6.88L12 17.77l-6.18 3.25L7 14.14 2 9.27l6.91-1.01L12 2z",
    clock: "M12 22a10 10 0 100-20 10 10 0 000 20z M12 6v6l4 2",
    link: "M10 13a5 5 0 007.54.54l3-3a5 5 0 00-7.07-7.07l-1.72 1.71 M14 11a5 5 0 00-7.54-.54l-3 3a5 5 0 007.07 7.07l1.71-1.71",
    person: "M20 21v-2a4 4 0 00-4-4H8a4 4 0 00-4 4v2 M12 11a4 4 0 100-8 4 4 0 000 8z",
    map: "M1 6v16l7-4 8 4 7-4V2l-7 4-8-4-7 4z M8 2v16 M16 6v16",
    tag: "M20.59 13.41l-7.17 7.17a2 2 0 01-2.83 0L2 12V2h10l8.59 8.59a2 2 0 010 2.82z M7 7h.01",
    task: "M9 11l3 3L22 4 M21 12v7a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h11",
    warn: "M10.29 3.86L1.82 18a2 2 0 001.71 3h16.94a2 2 0 001.71-3L13.71 3.86a2 2 0 00-3.42 0z M12 9v4 M12 17h.01",
    phone: "M22 16.92v3a2 2 0 01-2.18 2 19.79 19.79 0 01-8.63-3.07 19.5 19.5 0 01-6-6 19.79 19.79 0 01-3.07-8.67A2 2 0 014.11 2h3a2 2 0 012 1.72c.127.96.361 1.903.7 2.81a2 2 0 01-.45 2.11L8.09 9.91a16 16 0 006 6l1.27-1.27a2 2 0 012.11-.45c.907.339 1.85.573 2.81.7A2 2 0 0122 16.92z",
    mail: "M4 4h16c1.1 0 2 .9 2 2v12c0 1.1-.9 2-2 2H4c-1.1 0-2-.9-2-2V6c0-1.1.9-2 2-2z M22 6l-10 7L2 6",
  };
  return (
    <svg width={size} height={size} viewBox="0 0 24 24" fill="none" stroke="currentColor" strokeWidth="2" strokeLinecap="round" strokeLinejoin="round">
      {(icons[name] || "").split(" M").map((d, i) => (
        <path key={i} d={i === 0 ? d : "M" + d} />
      ))}
    </svg>
  );
};

// ─── INITIAL DATA ─────────────────────────────────────────────────────────────
const INITIAL_MEMBERS = [
  {
    id: 1, name: "Carla Furtado", role: "Mãe / Responsável",
    phone: "", email: "", phoneModel: "",
    measures: { cintura: "70", quadril: "95", altura: "165", calca: "38", blusa: "M", sapato: "36", bust: "88" },
    color: "#e85d96"
  },
  {
    id: 2, name: "Vanessa", role: "Cônjuge",
    phone: "", email: "", phoneModel: "",
    measures: { cintura: "", quadril: "", altura: "", calca: "", blusa: "", sapato: "", bust: "" },
    color: "#8b5cf6"
  },
  {
    id: 3, name: "Lívia", role: "Filha",
    phone: "", email: "", phoneModel: "",
    measures: { cintura: "", quadril: "", altura: "", calca: "", blusa: "", sapato: "", bust: "" },
    color: "#f59e0b"
  },
  {
    id: 4, name: "Giovanna", role: "Filha",
    phone: "", email: "", phoneModel: "",
    measures: { cintura: "", quadril: "", altura: "", calca: "", blusa: "", sapato: "", bust: "" },
    color: "#10b981"
  },
];

const SHOPPING_CATEGORIES = ["Mercado", "Casa Praia", "Casa Caxias", "Farmácia", "Vestuário", "Outros"];
const TASK_CATEGORIES = ["Fazer", "Não Esquecer", "Lembrar", "Urgente", "Pessoal", "Trabalho"];

// ─── STORAGE ─────────────────────────────────────────────────────────────────
const useStorage = (key, init) => {
  const [val, setVal] = useState(() => {
    try {
      const s = localStorage.getItem(key);
      return s ? JSON.parse(s) : init;
    } catch { return init; }
  });
  useEffect(() => { try { localStorage.setItem(key, JSON.stringify(val)); } catch {} }, [key, val]);
  return [val, setVal];
};

// ─── MODAL ────────────────────────────────────────────────────────────────────
const Modal = ({ title, onClose, children }) => (
  <div style={{ position: "fixed", inset: 0, background: "rgba(0,0,0,0.6)", display: "flex", alignItems: "center", justifyContent: "center", zIndex: 1000, padding: "16px" }}>
    <div style={{ background: "#1a1a2e", border: "1px solid #2d2d4e", borderRadius: "16px", width: "100%", maxWidth: "560px", maxHeight: "90vh", overflow: "auto" }}>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", padding: "20px 24px 16px", borderBottom: "1px solid #2d2d4e" }}>
        <h3 style={{ margin: 0, color: "#fff", fontSize: "18px", fontFamily: "'Playfair Display', serif" }}>{title}</h3>
        <button onClick={onClose} style={{ background: "none", border: "none", color: "#888", cursor: "pointer" }}><Icon name="x" size={22} /></button>
      </div>
      <div style={{ padding: "20px 24px 24px" }}>{children}</div>
    </div>
  </div>
);

// ─── FORM INPUT ───────────────────────────────────────────────────────────────
const FInput = ({ label, value, onChange, type = "text", placeholder = "" }) => (
  <div style={{ marginBottom: "14px" }}>
    {label && <label style={{ display: "block", color: "#aaa", fontSize: "12px", marginBottom: "6px", textTransform: "uppercase", letterSpacing: "0.06em" }}>{label}</label>}
    <input
      type={type} value={value} onChange={e => onChange(e.target.value)}
      placeholder={placeholder}
      style={{ width: "100%", background: "#0d0d1a", border: "1px solid #2d2d4e", borderRadius: "8px", padding: "10px 14px", color: "#fff", fontSize: "14px", outline: "none", boxSizing: "border-box" }}
    />
  </div>
);

const FSelect = ({ label, value, onChange, options }) => (
  <div style={{ marginBottom: "14px" }}>
    {label && <label style={{ display: "block", color: "#aaa", fontSize: "12px", marginBottom: "6px", textTransform: "uppercase", letterSpacing: "0.06em" }}>{label}</label>}
    <select value={value} onChange={e => onChange(e.target.value)}
      style={{ width: "100%", background: "#0d0d1a", border: "1px solid #2d2d4e", borderRadius: "8px", padding: "10px 14px", color: "#fff", fontSize: "14px", outline: "none" }}>
      {options.map(o => <option key={o} value={o}>{o}</option>)}
    </select>
  </div>
);

// ─── BADGE ────────────────────────────────────────────────────────────────────
const Badge = ({ text, color = "#e85d96" }) => (
  <span style={{ background: color + "22", color, border: `1px solid ${color}44`, borderRadius: "20px", padding: "2px 10px", fontSize: "11px", fontWeight: 600 }}>{text}</span>
);

// ─── SECTION: FAMÍLIA (CADASTRO) ──────────────────────────────────────────────
const FamiliaSection = ({ members, setMembers }) => {
  const [modal, setModal] = useState(null); // null | member object
  const [form, setForm] = useState({});

  const openEdit = (m) => { setForm({ ...m, measures: { ...m.measures } }); setModal(m.id === -1 ? "new" : m.id); };
  const openNew = () => {
    setForm({ id: Date.now(), name: "", role: "", phone: "", email: "", phoneModel: "", color: "#6366f1", measures: { cintura: "", quadril: "", altura: "", calca: "", blusa: "", sapato: "", bust: "" } });
    setModal("new");
  };
  const save = () => {
    if (modal === "new") setMembers(p => [...p, form]);
    else setMembers(p => p.map(m => m.id === modal ? form : m));
    setModal(null);
  };
  const remove = (id) => setMembers(p => p.filter(m => m.id !== id));

  return (
    <div>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: "20px" }}>
        <h2 style={{ margin: 0, color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Família Furtado</h2>
        <button onClick={openNew} style={{ background: "#e85d96", border: "none", borderRadius: "10px", color: "#fff", padding: "9px 16px", cursor: "pointer", display: "flex", alignItems: "center", gap: "6px", fontSize: "13px", fontWeight: 600 }}>
          <Icon name="plus" size={16} /> Adicionar
        </button>
      </div>

      <div style={{ display: "grid", gap: "14px" }}>
        {members.map(m => (
          <div key={m.id} style={{ background: "#12122a", border: `1px solid ${m.color}33`, borderRadius: "14px", padding: "18px", display: "flex", gap: "16px", alignItems: "flex-start" }}>
            <div style={{ width: 46, height: 46, borderRadius: "50%", background: m.color + "33", border: `2px solid ${m.color}`, display: "flex", alignItems: "center", justifyContent: "center", flexShrink: 0, fontSize: "18px", fontWeight: 700, color: m.color }}>
              {m.name.charAt(0)}
            </div>
            <div style={{ flex: 1, minWidth: 0 }}>
              <div style={{ display: "flex", alignItems: "center", gap: "8px", marginBottom: "4px" }}>
                <span style={{ color: "#fff", fontWeight: 700, fontSize: "15px" }}>{m.name}</span>
                <Badge text={m.role || "Membro"} color={m.color} />
              </div>
              {m.phone && <div style={{ color: "#888", fontSize: "13px", marginBottom: "2px" }}>📞 {m.phone}</div>}
              {m.email && <div style={{ color: "#888", fontSize: "13px", marginBottom: "2px" }}>✉️ {m.email}</div>}
              {m.phoneModel && <div style={{ color: "#888", fontSize: "13px", marginBottom: "8px" }}>📱 {m.phoneModel}</div>}
              {/* Medidas */}
              <div style={{ display: "flex", flexWrap: "wrap", gap: "6px", marginTop: "8px" }}>
                {Object.entries(m.measures || {}).filter(([, v]) => v).map(([k, v]) => (
                  <span key={k} style={{ background: "#1e1e3a", borderRadius: "8px", padding: "3px 10px", fontSize: "12px", color: "#ccc" }}>
                    <span style={{ color: m.color }}>{k.charAt(0).toUpperCase() + k.slice(1)}</span> {v}
                    {k === "cintura" || k === "quadril" || k === "altura" || k === "bust" ? " cm" : k === "sapato" ? "" : ""}
                  </span>
                ))}
              </div>
            </div>
            <div style={{ display: "flex", gap: "6px" }}>
              <button onClick={() => openEdit(m)} style={{ background: "#1e1e3a", border: "none", borderRadius: "8px", padding: "7px", color: "#aaa", cursor: "pointer" }}><Icon name="edit" size={16} /></button>
              {m.id !== 1 && <button onClick={() => remove(m.id)} style={{ background: "#1e1e3a", border: "none", borderRadius: "8px", padding: "7px", color: "#f87171", cursor: "pointer" }}><Icon name="trash" size={16} /></button>}
            </div>
          </div>
        ))}
      </div>

      {modal !== null && (
        <Modal title={modal === "new" ? "Novo Membro" : "Editar Cadastro"} onClose={() => setModal(null)}>
          <FInput label="Nome completo" value={form.name} onChange={v => setForm(p => ({ ...p, name: v }))} />
          <FInput label="Função / Parentesco" value={form.role} onChange={v => setForm(p => ({ ...p, role: v }))} placeholder="Ex: Filha, Cônjuge..." />
          <FInput label="Telefone" value={form.phone} onChange={v => setForm(p => ({ ...p, phone: v }))} type="tel" />
          <FInput label="E-mail" value={form.email} onChange={v => setForm(p => ({ ...p, email: v }))} type="email" />
          <FInput label="Modelo do Celular" value={form.phoneModel} onChange={v => setForm(p => ({ ...p, phoneModel: v }))} placeholder="Ex: Samsung S24" />
          <div style={{ margin: "16px 0 10px", color: "#aaa", fontSize: "12px", textTransform: "uppercase", letterSpacing: "0.06em", display: "flex", alignItems: "center", gap: "8px" }}>
            <Icon name="ruler" size={14} /> Medidas
          </div>
          <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: "0 12px" }}>
            {[["cintura", "Cintura (cm)"], ["quadril", "Quadril (cm)"], ["bust", "Busto (cm)"], ["altura", "Altura (cm)"], ["calca", "Calça (tam.)"], ["blusa", "Blusa (tam.)"], ["sapato", "Sapato (nº)"]].map(([k, l]) => (
              <FInput key={k} label={l} value={form.measures?.[k] || ""} onChange={v => setForm(p => ({ ...p, measures: { ...p.measures, [k]: v } }))} />
            ))}
          </div>
          <div style={{ marginBottom: "14px" }}>
            <label style={{ display: "block", color: "#aaa", fontSize: "12px", marginBottom: "6px", textTransform: "uppercase" }}>Cor</label>
            <input type="color" value={form.color} onChange={e => setForm(p => ({ ...p, color: e.target.value }))} style={{ width: "48px", height: "36px", border: "none", borderRadius: "8px", cursor: "pointer", background: "none" }} />
          </div>
          <button onClick={save} style={{ width: "100%", background: "#e85d96", border: "none", borderRadius: "10px", color: "#fff", padding: "12px", cursor: "pointer", fontWeight: 700, fontSize: "15px" }}>Salvar</button>
        </Modal>
      )}
    </div>
  );
};

// ─── SECTION: TAREFAS ─────────────────────────────────────────────────────────
const TarefasSection = ({ members }) => {
  const [tasks, setTasks] = useStorage("ff_tasks", []);
  const [modal, setModal] = useState(false);
  const [filter, setFilter] = useState("Todas");
  const [form, setForm] = useState({ title: "", category: "Fazer", assignee: "", priority: "Normal", date: "", note: "" });

  const cats = ["Todas", ...TASK_CATEGORIES];
  const filtered = filter === "Todas" ? tasks : tasks.filter(t => t.category === filter);
  const pending = tasks.filter(t => !t.done).length;

  const addTask = () => {
    if (!form.title.trim()) return;
    setTasks(p => [...p, { ...form, id: Date.now(), done: false, createdAt: new Date().toISOString() }]);
    setForm({ title: "", category: "Fazer", assignee: "", priority: "Normal", date: "", note: "" });
    setModal(false);
  };
  const toggle = (id) => setTasks(p => p.map(t => t.id === id ? { ...t, done: !t.done } : t));
  const remove = (id) => setTasks(p => p.filter(t => t.id !== id));

  const priorityColor = { Urgente: "#ef4444", Alta: "#f59e0b", Normal: "#6366f1", Baixa: "#10b981" };

  return (
    <div>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: "16px" }}>
        <div>
          <h2 style={{ margin: "0 0 2px", color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Tarefas</h2>
          <span style={{ color: "#888", fontSize: "13px" }}>{pending} pendente{pending !== 1 ? "s" : ""}</span>
        </div>
        <button onClick={() => setModal(true)} style={{ background: "#6366f1", border: "none", borderRadius: "10px", color: "#fff", padding: "9px 16px", cursor: "pointer", display: "flex", alignItems: "center", gap: "6px", fontSize: "13px", fontWeight: 600 }}>
          <Icon name="plus" size={16} /> Nova
        </button>
      </div>

      <div style={{ display: "flex", gap: "8px", flexWrap: "wrap", marginBottom: "16px" }}>
        {cats.map(c => (
          <button key={c} onClick={() => setFilter(c)}
            style={{ background: filter === c ? "#6366f1" : "#12122a", border: `1px solid ${filter === c ? "#6366f1" : "#2d2d4e"}`, borderRadius: "20px", color: filter === c ? "#fff" : "#888", padding: "5px 14px", cursor: "pointer", fontSize: "12px", fontWeight: 600 }}>
            {c}
          </button>
        ))}
      </div>

      <div style={{ display: "grid", gap: "10px" }}>
        {filtered.length === 0 && <div style={{ color: "#555", textAlign: "center", padding: "32px", fontSize: "14px" }}>Nenhuma tarefa aqui ainda 🎉</div>}
        {filtered.map(t => (
          <div key={t.id} style={{ background: "#12122a", borderRadius: "12px", padding: "14px 16px", display: "flex", alignItems: "flex-start", gap: "12px", opacity: t.done ? 0.5 : 1, border: "1px solid #1e1e3a" }}>
            <button onClick={() => toggle(t.id)} style={{ width: 22, height: 22, borderRadius: "6px", background: t.done ? "#10b981" : "transparent", border: `2px solid ${t.done ? "#10b981" : "#444"}`, cursor: "pointer", flexShrink: 0, display: "flex", alignItems: "center", justifyContent: "center", color: "#fff", marginTop: "1px" }}>
              {t.done && <Icon name="check" size={13} />}
            </button>
            <div style={{ flex: 1, minWidth: 0 }}>
              <div style={{ color: t.done ? "#666" : "#fff", fontWeight: 600, fontSize: "14px", textDecoration: t.done ? "line-through" : "none" }}>{t.title}</div>
              <div style={{ display: "flex", gap: "6px", marginTop: "6px", flexWrap: "wrap" }}>
                <Badge text={t.category} color="#6366f1" />
                <Badge text={t.priority} color={priorityColor[t.priority] || "#6366f1"} />
                {t.assignee && <Badge text={t.assignee} color="#e85d96" />}
                {t.date && <Badge text={t.date} color="#888" />}
              </div>
              {t.note && <div style={{ color: "#666", fontSize: "12px", marginTop: "6px" }}>{t.note}</div>}
            </div>
            <button onClick={() => remove(t.id)} style={{ background: "none", border: "none", color: "#555", cursor: "pointer" }}><Icon name="trash" size={15} /></button>
          </div>
        ))}
      </div>

      {modal && (
        <Modal title="Nova Tarefa" onClose={() => setModal(false)}>
          <FInput label="Título da tarefa" value={form.title} onChange={v => setForm(p => ({ ...p, title: v }))} placeholder="O que precisa ser feito?" />
          <FSelect label="Categoria" value={form.category} onChange={v => setForm(p => ({ ...p, category: v }))} options={TASK_CATEGORIES} />
          <FSelect label="Prioridade" value={form.priority} onChange={v => setForm(p => ({ ...p, priority: v }))} options={["Urgente", "Alta", "Normal", "Baixa"]} />
          <FSelect label="Responsável" value={form.assignee} onChange={v => setForm(p => ({ ...p, assignee: v }))} options={["", ...members.map(m => m.name)]} />
          <FInput label="Data limite" value={form.date} onChange={v => setForm(p => ({ ...p, date: v }))} type="date" />
          <FInput label="Observação" value={form.note} onChange={v => setForm(p => ({ ...p, note: v }))} placeholder="Detalhes adicionais..." />
          <button onClick={addTask} style={{ width: "100%", background: "#6366f1", border: "none", borderRadius: "10px", color: "#fff", padding: "12px", cursor: "pointer", fontWeight: 700, fontSize: "15px" }}>Adicionar Tarefa</button>
        </Modal>
      )}
    </div>
  );
};

// ─── SECTION: AGENDA ──────────────────────────────────────────────────────────
const AgendaSection = ({ members }) => {
  const [events, setEvents] = useStorage("ff_events", []);
  const [modal, setModal] = useState(false);
  const [view, setView] = useState("coletiva");
  const [filterMember, setFilterMember] = useState("");
  const [form, setForm] = useState({ title: "", date: "", time: "", type: "coletiva", assignee: "", note: "", color: "#6366f1", googleSync: false });

  const displayed = events
    .filter(e => view === "coletiva" ? true : e.type === "individual")
    .filter(e => !filterMember || e.assignee === filterMember)
    .sort((a, b) => (a.date + a.time) > (b.date + b.time) ? 1 : -1);

  const addEvent = () => {
    if (!form.title || !form.date) return;
    setEvents(p => [...p, { ...form, id: Date.now() }]);
    setModal(false);
    if (form.googleSync) {
      const start = new Date(`${form.date}T${form.time || "09:00"}`);
      const end = new Date(start.getTime() + 60 * 60000);
      const url = `https://calendar.google.com/calendar/render?action=TEMPLATE&text=${encodeURIComponent(form.title)}&dates=${start.toISOString().replace(/[-:]/g, "").split(".")[0]}Z/${end.toISOString().replace(/[-:]/g, "").split(".")[0]}Z&details=${encodeURIComponent(form.note || "")}`;
      window.open(url, "_blank");
    }
  };
  const remove = (id) => setEvents(p => p.filter(e => e.id !== id));

  const today = new Date().toISOString().split("T")[0];
  const upcoming = displayed.filter(e => e.date >= today);
  const past = displayed.filter(e => e.date < today);

  return (
    <div>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: "16px" }}>
        <h2 style={{ margin: 0, color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Agenda</h2>
        <button onClick={() => setModal(true)} style={{ background: "#f59e0b", border: "none", borderRadius: "10px", color: "#000", padding: "9px 16px", cursor: "pointer", display: "flex", alignItems: "center", gap: "6px", fontSize: "13px", fontWeight: 700 }}>
          <Icon name="plus" size={16} /> Evento
        </button>
      </div>

      <div style={{ display: "flex", gap: "8px", marginBottom: "14px", flexWrap: "wrap" }}>
        {["coletiva", "individual"].map(v => (
          <button key={v} onClick={() => setView(v)}
            style={{ background: view === v ? "#f59e0b" : "#12122a", border: "none", borderRadius: "20px", color: view === v ? "#000" : "#888", padding: "6px 16px", cursor: "pointer", fontSize: "12px", fontWeight: 700, textTransform: "capitalize" }}>
            {v === "coletiva" ? "👨‍👩‍👧‍👧 Coletiva" : "👤 Individual"}
          </button>
        ))}
        <select value={filterMember} onChange={e => setFilterMember(e.target.value)}
          style={{ background: "#12122a", border: "1px solid #2d2d4e", borderRadius: "20px", color: "#888", padding: "5px 12px", fontSize: "12px", cursor: "pointer" }}>
          <option value="">Todos</option>
          {members.map(m => <option key={m.id} value={m.name}>{m.name}</option>)}
        </select>
      </div>

      {upcoming.length > 0 && (
        <div style={{ marginBottom: "20px" }}>
          <div style={{ color: "#f59e0b", fontSize: "12px", fontWeight: 700, marginBottom: "10px", textTransform: "uppercase", letterSpacing: "0.06em" }}>Próximos Eventos</div>
          <div style={{ display: "grid", gap: "10px" }}>
            {upcoming.map(e => <EventCard key={e.id} event={e} members={members} onRemove={remove} />)}
          </div>
        </div>
      )}
      {past.length > 0 && (
        <div>
          <div style={{ color: "#555", fontSize: "12px", fontWeight: 700, marginBottom: "10px", textTransform: "uppercase", letterSpacing: "0.06em" }}>Anteriores</div>
          <div style={{ display: "grid", gap: "10px", opacity: 0.6 }}>
            {past.slice(-5).map(e => <EventCard key={e.id} event={e} members={members} onRemove={remove} />)}
          </div>
        </div>
      )}
      {upcoming.length === 0 && past.length === 0 && <div style={{ color: "#555", textAlign: "center", padding: "32px", fontSize: "14px" }}>Nenhum evento cadastrado</div>}

      {modal && (
        <Modal title="Novo Evento" onClose={() => setModal(false)}>
          <FInput label="Título" value={form.title} onChange={v => setForm(p => ({ ...p, title: v }))} />
          <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: "0 12px" }}>
            <FInput label="Data" value={form.date} onChange={v => setForm(p => ({ ...p, date: v }))} type="date" />
            <FInput label="Horário" value={form.time} onChange={v => setForm(p => ({ ...p, time: v }))} type="time" />
          </div>
          <FSelect label="Tipo" value={form.type} onChange={v => setForm(p => ({ ...p, type: v }))} options={["coletiva", "individual"]} />
          <FSelect label="Participante principal" value={form.assignee} onChange={v => setForm(p => ({ ...p, assignee: v }))} options={["Família toda", ...members.map(m => m.name)]} />
          <FInput label="Observações" value={form.note} onChange={v => setForm(p => ({ ...p, note: v }))} placeholder="Local, detalhes..." />
          <div style={{ display: "flex", alignItems: "center", gap: "10px", margin: "12px 0" }}>
            <input type="checkbox" id="gsync" checked={form.googleSync} onChange={e => setForm(p => ({ ...p, googleSync: e.target.checked }))} style={{ width: 16, height: 16, cursor: "pointer" }} />
            <label htmlFor="gsync" style={{ color: "#aaa", fontSize: "13px", cursor: "pointer", display: "flex", alignItems: "center", gap: "6px" }}>
              <Icon name="link" size={14} /> Abrir no Google Agenda ao salvar
            </label>
          </div>
          <button onClick={addEvent} style={{ width: "100%", background: "#f59e0b", border: "none", borderRadius: "10px", color: "#000", padding: "12px", cursor: "pointer", fontWeight: 700, fontSize: "15px" }}>Salvar Evento</button>
        </Modal>
      )}
    </div>
  );
};

const EventCard = ({ event, members, onRemove }) => {
  const m = members.find(x => x.name === event.assignee);
  const color = m?.color || "#f59e0b";
  const fmt = (d) => d ? new Date(d + "T12:00:00").toLocaleDateString("pt-BR", { day: "2-digit", month: "short" }) : "";
  return (
    <div style={{ background: "#12122a", borderRadius: "12px", padding: "14px 16px", border: `1px solid ${color}33`, display: "flex", gap: "12px" }}>
      <div style={{ width: 42, height: 42, borderRadius: "10px", background: color + "22", border: `1px solid ${color}44`, display: "flex", flexDirection: "column", alignItems: "center", justifyContent: "center", flexShrink: 0 }}>
        <div style={{ color, fontSize: "11px", fontWeight: 700 }}>{event.date ? new Date(event.date + "T12:00:00").toLocaleDateString("pt-BR", { month: "short" }).toUpperCase() : ""}</div>
        <div style={{ color: "#fff", fontSize: "16px", fontWeight: 800, lineHeight: 1 }}>{event.date ? new Date(event.date + "T12:00:00").getDate() : ""}</div>
      </div>
      <div style={{ flex: 1 }}>
        <div style={{ color: "#fff", fontWeight: 600, fontSize: "14px" }}>{event.title}</div>
        <div style={{ display: "flex", gap: "6px", marginTop: "4px", flexWrap: "wrap" }}>
          {event.time && <Badge text={event.time} color="#888" />}
          {event.assignee && <Badge text={event.assignee} color={color} />}
          <Badge text={event.type} color="#6366f1" />
        </div>
        {event.note && <div style={{ color: "#666", fontSize: "12px", marginTop: "4px" }}>{event.note}</div>}
      </div>
      <button onClick={() => onRemove(event.id)} style={{ background: "none", border: "none", color: "#444", cursor: "pointer" }}><Icon name="trash" size={15} /></button>
    </div>
  );
};

// ─── SECTION: LEMBRETES ───────────────────────────────────────────────────────
const LembretesSection = ({ members }) => {
  const [reminders, setReminders] = useStorage("ff_reminders", []);
  const [modal, setModal] = useState(false);
  const [form, setForm] = useState({ text: "", date: "", time: "", assignee: "", repeat: "Não repete", priority: "Normal" });

  const add = () => {
    if (!form.text) return;
    setReminders(p => [...p, { ...form, id: Date.now(), done: false }]);
    setForm({ text: "", date: "", time: "", assignee: "", repeat: "Não repete", priority: "Normal" });
    setModal(false);
  };
  const toggle = (id) => setReminders(p => p.map(r => r.id === id ? { ...r, done: !r.done } : r));
  const remove = (id) => setReminders(p => p.filter(r => r.id !== id));
  const today = new Date().toISOString().split("T")[0];
  const pColor = { Urgente: "#ef4444", Alta: "#f59e0b", Normal: "#10b981", Baixa: "#6366f1" };

  return (
    <div>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: "20px" }}>
        <h2 style={{ margin: 0, color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Lembretes</h2>
        <button onClick={() => setModal(true)} style={{ background: "#10b981", border: "none", borderRadius: "10px", color: "#fff", padding: "9px 16px", cursor: "pointer", display: "flex", alignItems: "center", gap: "6px", fontSize: "13px", fontWeight: 600 }}>
          <Icon name="plus" size={16} /> Lembrete
        </button>
      </div>

      {/* Avisos vencendo hoje */}
      {reminders.filter(r => !r.done && r.date === today).length > 0 && (
        <div style={{ background: "#f59e0b22", border: "1px solid #f59e0b44", borderRadius: "12px", padding: "12px 16px", marginBottom: "16px", display: "flex", gap: "10px", alignItems: "flex-start" }}>
          <Icon name="warn" size={18} />
          <div>
            <div style={{ color: "#f59e0b", fontWeight: 700, fontSize: "13px" }}>⚠️ Lembretes para hoje</div>
            {reminders.filter(r => !r.done && r.date === today).map(r => (
              <div key={r.id} style={{ color: "#ccc", fontSize: "12px", marginTop: "2px" }}>• {r.text} {r.time && `às ${r.time}`}</div>
            ))}
          </div>
        </div>
      )}

      <div style={{ display: "grid", gap: "10px" }}>
        {reminders.length === 0 && <div style={{ color: "#555", textAlign: "center", padding: "32px", fontSize: "14px" }}>Nenhum lembrete ainda</div>}
        {[...reminders].sort((a, b) => (a.date || "9") > (b.date || "9") ? 1 : -1).map(r => (
          <div key={r.id} style={{ background: "#12122a", borderRadius: "12px", padding: "14px 16px", display: "flex", gap: "12px", opacity: r.done ? 0.45 : 1, border: "1px solid #1e1e3a" }}>
            <button onClick={() => toggle(r.id)} style={{ width: 22, height: 22, borderRadius: "50%", background: r.done ? "#10b981" : "transparent", border: `2px solid ${r.done ? "#10b981" : "#444"}`, cursor: "pointer", flexShrink: 0, display: "flex", alignItems: "center", justifyContent: "center", color: "#fff", marginTop: "1px" }}>
              {r.done && <Icon name="check" size={13} />}
            </button>
            <div style={{ flex: 1 }}>
              <div style={{ color: r.done ? "#555" : "#fff", fontWeight: 600, fontSize: "14px", textDecoration: r.done ? "line-through" : "none" }}>{r.text}</div>
              <div style={{ display: "flex", gap: "6px", marginTop: "6px", flexWrap: "wrap" }}>
                {r.date && <Badge text={new Date(r.date + "T12:00").toLocaleDateString("pt-BR")} color="#888" />}
                {r.time && <Badge text={r.time} color="#888" />}
                {r.assignee && <Badge text={r.assignee} color="#e85d96" />}
                <Badge text={r.priority} color={pColor[r.priority]} />
                {r.repeat !== "Não repete" && <Badge text={r.repeat} color="#6366f1" />}
              </div>
            </div>
            <button onClick={() => remove(r.id)} style={{ background: "none", border: "none", color: "#444", cursor: "pointer" }}><Icon name="trash" size={15} /></button>
          </div>
        ))}
      </div>

      {modal && (
        <Modal title="Novo Lembrete" onClose={() => setModal(false)}>
          <FInput label="Lembrete" value={form.text} onChange={v => setForm(p => ({ ...p, text: v }))} placeholder="O que precisa lembrar?" />
          <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: "0 12px" }}>
            <FInput label="Data" value={form.date} onChange={v => setForm(p => ({ ...p, date: v }))} type="date" />
            <FInput label="Horário" value={form.time} onChange={v => setForm(p => ({ ...p, time: v }))} type="time" />
          </div>
          <FSelect label="Para quem" value={form.assignee} onChange={v => setForm(p => ({ ...p, assignee: v }))} options={["Família toda", ...members.map(m => m.name)]} />
          <FSelect label="Prioridade" value={form.priority} onChange={v => setForm(p => ({ ...p, priority: v }))} options={["Urgente", "Alta", "Normal", "Baixa"]} />
          <FSelect label="Repetição" value={form.repeat} onChange={v => setForm(p => ({ ...p, repeat: v }))} options={["Não repete", "Diário", "Semanal", "Mensal", "Anual"]} />
          <button onClick={add} style={{ width: "100%", background: "#10b981", border: "none", borderRadius: "10px", color: "#fff", padding: "12px", cursor: "pointer", fontWeight: 700, fontSize: "15px" }}>Salvar Lembrete</button>
        </Modal>
      )}
    </div>
  );
};

// ─── SECTION: LISTA DE COMPRAS ────────────────────────────────────────────────
const ComprasSection = () => {
  const [lists, setLists] = useStorage("ff_shopping", {
    "Mercado": [], "Casa Praia": [], "Casa Caxias": [], "Farmácia": [], "Vestuário": [], "Outros": []
  });
  const [activeList, setActiveList] = useState("Mercado");
  const [newItem, setNewItem] = useState("");
  const [newQty, setNewQty] = useState("1");

  const items = lists[activeList] || [];
  const total = Object.values(lists).reduce((a, l) => a + l.length, 0);
  const pending = Object.values(lists).reduce((a, l) => a + l.filter(i => !i.done).length, 0);

  const add = () => {
    if (!newItem.trim()) return;
    setLists(p => ({ ...p, [activeList]: [...(p[activeList] || []), { id: Date.now(), name: newItem, qty: newQty, done: false }] }));
    setNewItem(""); setNewQty("1");
  };
  const toggle = (id) => setLists(p => ({ ...p, [activeList]: p[activeList].map(i => i.id === id ? { ...i, done: !i.done } : i) }));
  const remove = (id) => setLists(p => ({ ...p, [activeList]: p[activeList].filter(i => i.id !== id) }));
  const clearDone = () => setLists(p => ({ ...p, [activeList]: p[activeList].filter(i => !i.done) }));

  const listIcons = { "Mercado": "🛒", "Casa Praia": "🏖️", "Casa Caxias": "🏠", "Farmácia": "💊", "Vestuário": "👗", "Outros": "📦" };

  return (
    <div>
      <div style={{ display: "flex", justifyContent: "space-between", alignItems: "center", marginBottom: "4px" }}>
        <h2 style={{ margin: 0, color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Lista de Compras</h2>
      </div>
      <div style={{ color: "#888", fontSize: "13px", marginBottom: "16px" }}>{pending} de {total} itens pendentes</div>

      <div style={{ display: "flex", gap: "8px", flexWrap: "wrap", marginBottom: "16px" }}>
        {SHOPPING_CATEGORIES.map(c => {
          const cnt = (lists[c] || []).filter(i => !i.done).length;
          return (
            <button key={c} onClick={() => setActiveList(c)}
              style={{ background: activeList === c ? "#e85d96" : "#12122a", border: `1px solid ${activeList === c ? "#e85d96" : "#2d2d4e"}`, borderRadius: "10px", color: activeList === c ? "#fff" : "#888", padding: "7px 14px", cursor: "pointer", fontSize: "12px", fontWeight: 600, position: "relative" }}>
              {listIcons[c]} {c} {cnt > 0 && <span style={{ background: "#ef4444", color: "#fff", borderRadius: "10px", padding: "1px 6px", fontSize: "10px", marginLeft: "4px" }}>{cnt}</span>}
            </button>
          );
        })}
      </div>

      <div style={{ display: "flex", gap: "8px", marginBottom: "16px" }}>
        <input value={newQty} onChange={e => setNewQty(e.target.value)} placeholder="Qtd" style={{ width: "60px", background: "#12122a", border: "1px solid #2d2d4e", borderRadius: "8px", padding: "10px", color: "#fff", fontSize: "14px", outline: "none" }} />
        <input value={newItem} onChange={e => setNewItem(e.target.value)} onKeyDown={e => e.key === "Enter" && add()} placeholder="Adicionar item..." style={{ flex: 1, background: "#12122a", border: "1px solid #2d2d4e", borderRadius: "8px", padding: "10px 14px", color: "#fff", fontSize: "14px", outline: "none" }} />
        <button onClick={add} style={{ background: "#e85d96", border: "none", borderRadius: "8px", padding: "10px 16px", color: "#fff", cursor: "pointer" }}><Icon name="plus" size={18} /></button>
      </div>

      <div style={{ display: "grid", gap: "8px" }}>
        {items.length === 0 && <div style={{ color: "#555", textAlign: "center", padding: "24px", fontSize: "14px" }}>Lista vazia — adicione itens acima</div>}
        {items.map(item => (
          <div key={item.id} style={{ background: "#12122a", borderRadius: "10px", padding: "12px 14px", display: "flex", alignItems: "center", gap: "10px", border: "1px solid #1e1e3a" }}>
            <button onClick={() => toggle(item.id)} style={{ width: 20, height: 20, borderRadius: "5px", background: item.done ? "#10b981" : "transparent", border: `2px solid ${item.done ? "#10b981" : "#444"}`, cursor: "pointer", flexShrink: 0, display: "flex", alignItems: "center", justifyContent: "center", color: "#fff" }}>
              {item.done && <Icon name="check" size={12} />}
            </button>
            <span style={{ flex: 1, color: item.done ? "#555" : "#fff", textDecoration: item.done ? "line-through" : "none", fontSize: "14px" }}>{item.name}</span>
            <span style={{ color: "#888", fontSize: "12px", background: "#1e1e3a", borderRadius: "6px", padding: "2px 8px" }}>x{item.qty}</span>
            <button onClick={() => remove(item.id)} style={{ background: "none", border: "none", color: "#444", cursor: "pointer" }}><Icon name="trash" size={14} /></button>
          </div>
        ))}
      </div>
      {items.some(i => i.done) && (
        <button onClick={clearDone} style={{ marginTop: "12px", background: "none", border: "1px solid #2d2d4e", borderRadius: "8px", color: "#666", padding: "8px 16px", cursor: "pointer", fontSize: "13px", width: "100%" }}>
          Limpar itens marcados
        </button>
      )}
    </div>
  );
};

// ─── SECTION: MEDIDAS ─────────────────────────────────────────────────────────
const MedidasSection = ({ members }) => {
  const [sel, setSel] = useState(members[0]?.id);
  const member = members.find(m => m.id === sel);

  const measureLabels = {
    cintura: ["Cintura", "cm", "📏"],
    quadril: ["Quadril", "cm", "📏"],
    bust: ["Busto", "cm", "📏"],
    altura: ["Altura", "cm", "📐"],
    calca: ["Calça", "tam.", "👖"],
    blusa: ["Blusa / Vestido", "tam.", "👕"],
    sapato: ["Calçado", "nº", "👟"],
  };

  const sizeGuide = {
    calca: { "34": "68-72cm", "36": "72-76cm", "38": "76-80cm", "40": "80-84cm", "42": "84-88cm", "44": "88-92cm", "PP": "até 72cm", "P": "72-76cm", "M": "76-80cm", "G": "80-88cm", "GG": "88-96cm" },
    blusa: { "PP": "Busto 80-84cm", "P": "Busto 84-88cm", "M": "Busto 88-92cm", "G": "Busto 92-98cm", "GG": "Busto 98-104cm", "XGG": "Busto 104-110cm" },
  };

  return (
    <div>
      <h2 style={{ margin: "0 0 16px", color: "#fff", fontFamily: "'Playfair Display', serif", fontSize: "22px" }}>Medidas & Tamanhos</h2>

      <div style={{ display: "flex", gap: "8px", flexWrap: "wrap", marginBottom: "20px" }}>
        {members.map(m => (
          <button key={m.id} onClick={() => setSel(m.id)}
            style={{ background: sel === m.id ? m.color : "#12122a", border: `2px solid ${m.color}${sel === m.id ? "ff" : "44"}`, borderRadius: "10px", color: sel === m.id ? "#fff" : "#888", padding: "7px 16px", cursor: "pointer", fontSize: "13px", fontWeight: 700 }}>
            {m.name.split(" ")[0]}
          </button>
        ))}
      </div>

      {member && (
        <>
          <div style={{ display: "flex", alignItems: "center", gap: "12px", marginBottom: "20px" }}>
            <div style={{ width: 50, height: 50, borderRadius: "50%", background: member.color + "22", border: `2px solid ${member.color}`, display: "flex", alignItems: "center", justifyContent: "center", fontSize: "22px", fontWeight: 700, color: member.color }}>{member.name.charAt(0)}</div>
            <div>
              <div style={{ color: "#fff", fontWeight: 700, fontSize: "16px" }}>{member.name}</div>
              <div style={{ color: "#888", fontSize: "13px" }}>{member.role}</div>
            </div>
          </div>

          <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: "10px", marginBottom: "24px" }}>
            {Object.entries(measureLabels).map(([k, [label, unit, emoji]]) => {
              const val = member.measures?.[k];
              return (
                <div key={k} style={{ background: "#12122a", borderRadius: "12px", padding: "16px", border: `1px solid ${val ? member.color + "44" : "#1e1e3a"}` }}>
                  <div style={{ color: "#666", fontSize: "11px", marginBottom: "6px", textTransform: "uppercase" }}>{emoji} {label}</div>
                  {val ? (
                    <div style={{ color: "#fff", fontSize: "22px", fontWeight: 800 }}>{val} <span style={{ fontSize: "13px", color: "#888", fontWeight: 400 }}>{unit}</span></div>
                  ) : (
                    <div style={{ color: "#444", fontSize: "14px", fontStyle: "italic" }}>Não informado</div>
                  )}
                </div>
              );
            })}
          </div>

          {/* Guia de tamanhos */}
          <div style={{ background: "#0d0d1a", borderRadius: "12px", padding: "16px", border: "1px solid #1e1e3a" }}>
            <div style={{ color: "#aaa", fontSize: "12px", fontWeight: 700, marginBottom: "12px", textTransform: "uppercase", letterSpacing: "0.06em" }}>📋 Guia de Tamanhos BR</div>
            {["calca", "blusa"].map(k => (
              <div key={k} style={{ marginBottom: "12px" }}>
                <div style={{ color: "#888", fontSize: "12px", marginBottom: "6px", textTransform: "capitalize" }}>{k === "calca" ? "👖 Calça" : "👕 Blusa / Vestido"}</div>
                <div style={{ display: "flex", flexWrap: "wrap", gap: "6px" }}>
                  {Object.entries(sizeGuide[k]).map(([size, ref]) => (
                    <div key={size} style={{ background: member.measures?.[k] === size ? member.color + "33" : "#1a1a2e", border: `1px solid ${member.measures?.[k] === size ? member.color : "#2d2d4e"}`, borderRadius: "8px", padding: "4px 10px", fontSize: "11px" }}>
                      <span style={{ color: member.measures?.[k] === size ? member.color : "#ccc", fontWeight: 700 }}>{size}</span>
                      <span style={{ color: "#555", marginLeft: "4px" }}>{ref}</span>
                    </div>
                  ))}
                </div>
              </div>
            ))}
          </div>
        </>
      )}
    </div>
  );
};

// ─── MAIN APP ─────────────────────────────────────────────────────────────────
export default function App() {
  const [members, setMembers] = useStorage("ff_members", INITIAL_MEMBERS);
  const [tab, setTab] = useState("home");

  const tabs = [
    { id: "home", label: "Início", icon: "home" },
    { id: "familia", label: "Família", icon: "users" },
    { id: "tarefas", label: "Tarefas", icon: "task" },
    { id: "agenda", label: "Agenda", icon: "calendar" },
    { id: "lembretes", label: "Lembretes", icon: "bell" },
    { id: "compras", label: "Compras", icon: "shopping" },
    { id: "medidas", label: "Medidas", icon: "ruler" },
  ];

  const [tasks] = useStorage("ff_tasks", []);
  const [events] = useStorage("ff_events", []);
  const [reminders] = useStorage("ff_reminders", []);
  const [lists] = useStorage("ff_shopping", { "Mercado": [], "Casa Praia": [], "Casa Caxias": [], "Farmácia": [], "Vestuário": [], "Outros": [] });

  const today = new Date().toISOString().split("T")[0];
  const stats = {
    tasks: tasks.filter(t => !t.done).length,
    events: events.filter(e => e.date >= today).length,
    reminders: reminders.filter(r => !r.done).length,
    shopping: Object.values(lists).reduce((a, l) => a + l.filter(i => !i.done).length, 0),
  };

  const greeting = () => {
    const h = new Date().getHours();
    if (h < 12) return "Bom dia";
    if (h < 18) return "Boa tarde";
    return "Boa noite";
  };

  return (
    <div style={{ minHeight: "100vh", background: "#0a0a1a", fontFamily: "'DM Sans', system-ui, sans-serif", color: "#fff", paddingBottom: "80px" }}>
      <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700;800&family=DM+Sans:wght@400;500;600;700&display=swap" rel="stylesheet" />

      {/* HEADER */}
      <div style={{ background: "linear-gradient(135deg, #1a0a2e 0%, #0a0a1a 100%)", padding: "24px 20px 20px", borderBottom: "1px solid #1e1e3a" }}>
        <div style={{ display: "flex", justifyContent: "space-between", alignItems: "flex-start" }}>
          <div>
            <div style={{ color: "#e85d96", fontSize: "12px", fontWeight: 700, letterSpacing: "0.1em", textTransform: "uppercase", marginBottom: "4px" }}>Família</div>
            <h1 style={{ margin: 0, fontFamily: "'Playfair Display', serif", fontSize: "26px", fontWeight: 800, lineHeight: 1.1 }}>Furtado</h1>
            <div style={{ color: "#888", fontSize: "13px", marginTop: "4px" }}>{greeting()}, Carla 👋</div>
          </div>
          <div style={{ display: "flex", gap: "8px" }}>
            {members.slice(0, 4).map(m => (
              <div key={m.id} title={m.name} style={{ width: 36, height: 36, borderRadius: "50%", background: m.color + "22", border: `2px solid ${m.color}`, display: "flex", alignItems: "center", justifyContent: "center", fontSize: "14px", fontWeight: 700, color: m.color }}>
                {m.name.charAt(0)}
              </div>
            ))}
          </div>
        </div>
      </div>

      {/* CONTENT */}
      <div style={{ padding: "20px" }}>
        {tab === "home" && (
          <div>
            <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr", gap: "12px", marginBottom: "24px" }}>
              {[
                { label: "Tarefas", val: stats.tasks, icon: "task", color: "#6366f1", sub: "pendentes", tab: "tarefas" },
                { label: "Eventos", val: stats.events, icon: "calendar", color: "#f59e0b", sub: "próximos", tab: "agenda" },
                { label: "Lembretes", val: stats.reminders, icon: "bell", color: "#10b981", sub: "ativos", tab: "lembretes" },
                { label: "Compras", val: stats.shopping, icon: "shopping", color: "#e85d96", sub: "itens", tab: "compras" },
              ].map(s => (
                <button key={s.tab} onClick={() => setTab(s.tab)}
                  style={{ background: "#12122a", border: `1px solid ${s.color}33`, borderRadius: "14px", padding: "16px", textAlign: "left", cursor: "pointer", transition: "all 0.2s" }}>
                  <div style={{ color: s.color, marginBottom: "8px" }}><Icon name={s.icon} size={22} /></div>
                  <div style={{ color: "#fff", fontSize: "28px", fontWeight: 800, lineHeight: 1 }}>{s.val}</div>
                  <div style={{ color: "#888", fontSize: "12px", marginTop: "4px" }}>{s.label} {s.sub}</div>
                </button>
              ))}
            </div>

            <div style={{ background: "#12122a", borderRadius: "14px", padding: "16px", marginBottom: "16px", border: "1px solid #1e1e3a" }}>
              <div style={{ color: "#aaa", fontSize: "12px", fontWeight: 700, marginBottom: "12px", textTransform: "uppercase", letterSpacing: "0.06em" }}>⚡ Atalhos Rápidos</div>
              <div style={{ display: "grid", gridTemplateColumns: "1fr 1fr 1fr", gap: "8px" }}>
                {tabs.slice(1).map(t => (
                  <button key={t.id} onClick={() => setTab(t.id)}
                    style={{ background: "#1a1a2e", border: "1px solid #2d2d4e", borderRadius: "10px", padding: "12px 8px", cursor: "pointer", display: "flex", flexDirection: "column", alignItems: "center", gap: "6px" }}>
                    <span style={{ color: "#888" }}><Icon name={t.icon} size={18} /></span>
                    <span style={{ color: "#ccc", fontSize: "11px", fontWeight: 600 }}>{t.label}</span>
                  </button>
                ))}
              </div>
            </div>

            {/* Today's reminders */}
            {reminders.filter(r => !r.done && r.date === today).length > 0 && (
              <div style={{ background: "#f59e0b11", border: "1px solid #f59e0b44", borderRadius: "14px", padding: "14px 16px" }}>
                <div style={{ color: "#f59e0b", fontWeight: 700, marginBottom: "8px", fontSize: "13px" }}>🔔 Lembretes de Hoje</div>
                {reminders.filter(r => !r.done && r.date === today).map(r => (
                  <div key={r.id} style={{ color: "#ccc", fontSize: "13px", marginBottom: "4px" }}>• {r.text} {r.time && `– ${r.time}`}</div>
                ))}
              </div>
            )}
          </div>
        )}
        {tab === "familia" && <FamiliaSection members={members} setMembers={setMembers} />}
        {tab === "tarefas" && <TarefasSection members={members} />}
        {tab === "agenda" && <AgendaSection members={members} />}
        {tab === "lembretes" && <LembretesSection members={members} />}
        {tab === "compras" && <ComprasSection />}
        {tab === "medidas" && <MedidasSection members={members} />}
      </div>

      {/* BOTTOM NAV */}
      <div style={{ position: "fixed", bottom: 0, left: 0, right: 0, background: "#0d0d1a", borderTop: "1px solid #1e1e3a", display: "flex", padding: "8px 0 12px" }}>
        {tabs.map(t => (
          <button key={t.id} onClick={() => setTab(t.id)}
            style={{ flex: 1, background: "none", border: "none", cursor: "pointer", display: "flex", flexDirection: "column", alignItems: "center", gap: "4px", padding: "4px" }}>
            <span style={{ color: tab === t.id ? "#e85d96" : "#444", transition: "color 0.2s" }}><Icon name={t.icon} size={tab === t.id ? 22 : 20} /></span>
            <span style={{ color: tab === t.id ? "#e85d96" : "#555", fontSize: "9px", fontWeight: tab === t.id ? 700 : 400, letterSpacing: "0.03em" }}>{t.label}</span>
          </button>
        ))}
      </div>
    </div>
  );
}
