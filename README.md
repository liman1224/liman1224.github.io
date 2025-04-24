export default function HomePage() {
  return (
    <main className="min-h-screen bg-white text-gray-800 px-6 py-12">
      <section className="max-w-4xl mx-auto">
        <h1 className="text-4xl font-bold mb-4">Dr. Man Li</h1>
        <h2 className="text-xl font-medium mb-2">Assistant Professor, Department of Semiconductor Physics</h2>
        <p className="text-lg mb-4">Gachon University</p>
        <p className="mb-6">Email: <a href="mailto:liman1224@gachon.ac.kr" className="text-blue-600 hover:underline">liman1224@gachon.ac.kr</a></p>

        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-2">About Me</h3>
          <p className="text-base leading-relaxed">
            I am an assistant professor at Gachon University specializing in energy storage materials,
            including Li-ion and Zn-ion batteries, MXene quantum dots, metal-organic frameworks (MOFs),
            and advanced electrode/electrolyte designs. My research integrates both experimental approaches
            and DFT-based computational methods.
          </p>
        </section>

        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-2">Research Interests</h3>
          <ul className="list-disc list-inside space-y-1">
            <li>Li-ion and Zn-ion battery electrodes</li>
            <li>MXene QDs, MOFs, doped carbon, and DNA-based frameworks</li>
            <li>Lithium-sulfur battery performance enhancement</li>
            <li>Solid-state and cryogenic battery technologies</li>
            <li>DFT-based material simulations and experimental validation</li>
          </ul>
        </section>

        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-2">Curriculum Vitae</h3>
          <p>You can download my CV here: <a href="/cv.pdf" className="text-blue-600 hover:underline">CV.pdf</a></p>
        </section>

        <section className="mb-12">
          <h3 className="text-2xl font-semibold mb-2">Contact</h3>
          <p>Email: <a href="mailto:liman1224@gachon.ac.kr" className="text-blue-600 hover:underline">liman1224@gachon.ac.kr</a></p>
          <p>LinkedIn / ORCID (Add links here if available)</p>
        </section>
      </section>
    </main>
  );
}
