import { Card, CardContent } from "@/components/ui/card"; import { Button } from "@/components/ui/button"; import { Plane, Hotel, Car, Ship } from "lucide-react";

export default function HananeVoyageSite() { return ( <main className="min-h-screen bg-gradient-to-b from-blue-100 to-white p-6"> <section className="text-center mb-10"> <h1 className="text-4xl font-bold text-blue-800 mb-2">Hanane Voyage</h1> <p className="text-lg text-gray-700">سافر معنا بأسعار ممتازة وخدمة موثوقة!</p> </section>

<section className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 mb-10">
    <Card className="text-center shadow-xl p-4">
      <CardContent>
        <Ship className="mx-auto text-blue-600" size={48} />
        <h2 className="text-xl font-semibold mt-2">حجوزات البواخر</h2>
        <p className="text-sm text-gray-600">احجز تذكرة باخرة بسهولة لأي وجهة بحرية.</p>
        <Button className="mt-4 w-full bg-blue-600 text-white hover:bg-blue-700">احجز الآن</Button>
      </CardContent>
    </Card>

    <Card className="text-center shadow-xl p-4">
      <CardContent>
        <Hotel className="mx-auto text-blue-600" size={48} />
        <h2 className="text-xl font-semibold mt-2">فنادق</h2>
        <p className="text-sm text-gray-600">أفضل عروض الإقامة بأسعار مناسبة.</p>
        <Button className="mt-4 w-full bg-blue-600 text-white hover:bg-blue-700">احجز فندقك</Button>
      </CardContent>
    </Card>

    <Card className="text-center shadow-xl p-4">
      <CardContent>
        <Plane className="mx-auto text-blue-600" size={48} />
        <h2 className="text-xl font-semibold mt-2">تذاكر طيران</h2>
        <p className="text-sm text-gray-600">رحلات دولية ومحلية بأفضل الأسعار.</p>
        <Button className="mt-4 w-full bg-blue-600 text-white hover:bg-blue-700">احجز رحلتك</Button>
      </CardContent>
    </Card>

    <Card className="text-center shadow-xl p-4">
      <CardContent>
        <Car className="mx-auto text-blue-600" size={48} />
        <h2 className="text-xl font-semibold mt-2">تأجير سيارات</h2>
        <p className="text-sm text-gray-600">سيارات مريحة للإيجار داخل وخارج البلد.</p>
        <Button className="mt-4 w-full bg-blue-600 text-white hover:bg-blue-700">استأجر الآن</Button>
      </CardContent>
    </Card>
  </section>

  <footer className="text-center text-gray-500 text-sm mt-10">
    &copy; 2025 Hanane Voyage. جميع الحقوق محفوظة.
  </footer>
</main>

); }

