import Head from 'next/head';

export default function Home() {
  return (
    <div className="min-h-screen bg-gradient-to-br from-[#0F172A] to-[#1E293B] text-white font-sans">
      <Head>
        <title>SmartSync - توسعه نرم افزار</title>
        <meta name="viewport" content="width=device-width, initial-scale=1" />
      </Head>
      <header className="flex justify-between items-center p-6 bg-opacity-90 backdrop-blur bg-[#0F172A]">
        <img src="/SmartSync_Professional_Logo.svg" alt="SmartSync Logo" className="h-12" />
        <nav className="flex space-x-6 space-x-reverse">
          <a href="#about" className="hover:text-green-400">درباره ما</a>
          <a href="#services" className="hover:text-green-400">خدمات</a>
          <a href="#team" className="hover:text-green-400">تیم ما</a>
          <a href="#contact" className="hover:text-green-400">تماس با ما</a>
        </nav>
      </header>
      <main>
        <section className="text-center py-20 bg-gradient-to-t from-[#1E293B] to-[#0F172A]">
          <h1 className="text-4xl md:text-6xl font-bold text-green-400">SmartSync</h1>
          <p className="text-lg md:text-2xl text-slate-300 mt-4">توسعه نرم‌افزارهای خلاقانه برای آینده‌ی دیجیتال شما</p>
          <button className="mt-8 bg-green-400 text-[#0F172A] py-3 px-6 rounded-xl font-bold hover:bg-teal-300">شروع همکاری</button>
        </section>
        <section id="about" className="text-center py-16">
          <h2 className="text-3xl font-bold mb-4">درباره SmartSync</h2>
          <p className="max-w-2xl mx-auto text-slate-300">ما در SmartSync با تیمی متخصص، خلاق و دوستانه، بهترین راهکارهای توسعه نرم‌افزار تحت وب را برای کسب‌وکارها خلق می‌کنیم.</p>
        </section>
        <section id="services" className="py-16">
          <h2 className="text-3xl font-bold text-center">خدمات ما</h2>
          <div className="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10 p-6">
            {['توسعه نرم‌افزارهای تحت وب', 'طراحی وب‌سایت شرکتی و فروشگاهی', 'طراحی UI/UX حرفه‌ای', 'توسعه اپلیکیشن‌های PWA', 'طراحی و توسعه API اختصاصی', 'مشاوره فنی و تکنولوژیک', 'سئو تکنیکال و بهینه‌سازی', 'پشتیبانی و نگهداری پروژه', 'امنیت و تست نرم‌افزار', 'طراحی برندینگ دیجیتال'].map(service => (
              <div key={service} className="bg-[#1E293B] p-6 rounded-xl hover:bg-[#334155] transition">
                <p>{service}</p>
              </div>
            ))}
          </div>
        </section>
        <section id="team" className="py-16">
          <h2 className="text-3xl font-bold text-center">تیم ما</h2>
          <div className="grid grid-cols-1 md:grid-cols-3 gap-8 mt-10 p-6">
            {[
              'رزا خرمی - بنیانگذار و مدیر فروش',
              'مسعود - مدیر بازاریابی',
              'محمد باقر - مدیر محصول',
              'محمد حسینی - توسعه‌دهنده هوش مصنوعی',
              'دانیال عشقی - توسعه‌دهنده بک‌اند',
              'محمود محمودی نیک - توسعه‌دهنده فرانت‌اند',
              'کیمیا صادقی - توسعه‌دهنده فرانت‌اند',
            ].map(member => (
              <div key={member} className="bg-[#1E293B] p-6 rounded-xl hover:bg-[#334155] transition">
                <p>{member}</p>
              </div>
            ))}
          </div>
        </section>
        <section id="contact" className="py-16">
          <div className="max-w-lg mx-auto bg-[#0F172A] p-8 rounded-xl text-center">
            <h2 className="text-3xl font-bold mb-4">ارتباط با ما</h2>
            <p className="mb-2">ایمیل: info@smartsync.com</p>
            <p>واتساپ: 0912-123-4567</p>
          </div>
        </section>
      </main>
      <footer className="text-center text-sm py-6 bg-opacity-90 backdrop-blur bg-[#0F172A]">
        © 2025 SmartSync - تمامی حقوق محفوظ است
      </footer>
    </div>
  );
}
