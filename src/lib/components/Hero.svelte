<script>
</script>

<section class="pt-20 pb-16 text-center max-w-[1200px] mx-auto px-6">
  <h1 class="text-6xl font-bold tracking-tight text-gray-900 mb-6 leading-[1.1]">
    Transform Legacy Systems<br>Without the Risk
  </h1>
  <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto leading-relaxed">
    Element automates the modernization of legacy systems through intelligent analysis, incremental refactoring, and continuous evolution—no risky rewrites required.
  </p>
  <button class="bg-black text-white px-6 py-3 rounded-lg hover:bg-gray-800 transition-colors font-semibold text-sm mb-20 cursor-pointer">
    Get started
  </button>

  <!-- Code Transformation Visualization -->
  <div class="relative w-full aspect-[2/1] bg-gradient-to-br from-gray-900 to-gray-800 rounded-xl overflow-hidden flex items-center justify-center border border-gray-700">
    <!-- Legacy Code Block (Left) -->
    <div class="absolute left-[10%] top-[50%] transform -translate-y-1/2 w-[35%] h-[70%] bg-gray-800 rounded-lg border border-gray-600 p-4 shadow-2xl">
      <div class="flex items-center gap-2 mb-3 pb-2 border-b border-gray-700">
        <div class="w-2 h-2 rounded-full bg-red-500"></div>
        <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
        <div class="w-2 h-2 rounded-full bg-green-500"></div>
        <span class="text-[10px] text-gray-400 ml-2 font-mono">legacy_system.cbl</span>
      </div>
      <div class="space-y-2 text-[10px] font-mono opacity-60">
        <div class="text-yellow-400">IDENTIFICATION DIVISION.</div>
        <div class="text-gray-400">PROGRAM-ID. LEGACY-APP.</div>
        <div class="text-yellow-400">DATA DIVISION.</div>
        <div class="text-gray-400">WORKING-STORAGE SECTION.</div>
        <div class="text-blue-400">01 CUSTOMER-RECORD.</div>
        <div class="text-gray-400 pl-4">05 CUST-ID PIC 9(8).</div>
        <div class="text-gray-400 pl-4">05 CUST-NAME PIC X(30).</div>
        <div class="text-yellow-400">PROCEDURE DIVISION.</div>
        <div class="text-gray-400">PERFORM MAIN-LOGIC.</div>
      </div>
    </div>
    
    <!-- Arrow/Transformation Indicator -->
    <div class="absolute left-[47%] top-[50%] transform -translate-y-1/2 z-20">
      <div class="flex items-center gap-2">
        <div class="w-12 h-12 rounded-full bg-gradient-to-r from-purple-600 to-blue-600 flex items-center justify-center shadow-lg">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="white" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
            <path d="M5 12h14M12 5l7 7-7 7"/>
          </svg>
        </div>
      </div>
    </div>
    
    <!-- Modern Code Block (Right) -->
    <div class="absolute right-[10%] top-[50%] transform -translate-y-1/2 w-[35%] h-[70%] bg-gray-900 rounded-lg border border-purple-500/30 p-4 shadow-2xl">
      <div class="flex items-center gap-2 mb-3 pb-2 border-b border-gray-700">
        <div class="w-2 h-2 rounded-full bg-red-500"></div>
        <div class="w-2 h-2 rounded-full bg-yellow-500"></div>
        <div class="w-2 h-2 rounded-full bg-green-500"></div>
        <span class="text-[10px] text-gray-400 ml-2 font-mono">customer_service.java</span>
      </div>
      <div class="space-y-2 text-[10px] font-mono">
        <div class="text-purple-400">public class CustomerService {</div>
        <div class="text-gray-400 pl-4">@Autowired</div>
        <div class="text-blue-400 pl-4">private CustomerRepository repo;</div>
        <div class="text-gray-400 pl-4"></div>
        <div class="text-purple-400 pl-4">public Customer getCustomer(</div>
        <div class="text-blue-400 pl-8">Long customerId) {</div>
        <div class="text-gray-400 pl-8">return repo.findById(</div>
        <div class="text-gray-400 pl-12">customerId);</div>
        <div class="text-gray-400 pl-4">}</div>
        <div class="text-purple-400">}</div>
      </div>
    </div>
    
    <div class="absolute inset-0 bg-gradient-to-t from-gray-900/50 via-transparent to-transparent pointer-events-none"></div>
  </div>

  <div class="grid grid-cols-1 md:grid-cols-3 gap-12 mt-20 text-left">
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">01</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Automated Analysis</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Deep understanding of your legacy codebase through AI-powered analysis. Identify dependencies, business logic, and transformation opportunities automatically.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">02</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Incremental Refactoring</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Transform your systems piece by piece, not all at once. Maintain business continuity while modernizing at your own pace with validated transformations.
      </p>
    </div>
    <div>
      <div class="text-xs font-semibold text-gray-400 mb-2">03</div>
      <h3 class="text-xl font-bold text-gray-900 mb-2">Continuous Evolution</h3>
      <p class="text-sm text-gray-500 leading-relaxed">
        Keep your modernized systems up-to-date with ongoing platform improvements. You own the code, we provide the transformation expertise.
      </p>
    </div>
  </div>
</section>
