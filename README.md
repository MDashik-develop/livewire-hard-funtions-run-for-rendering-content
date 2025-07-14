# livewire-hard-funtions-run-for-rendering-content

        <script>
            function initializeExample() {
                // website load navigate content get right function work
            }
        
            // Call on all Livewire lifecycle events
            document.addEventListener('DOMContentLoaded', initializeExample);
            document.addEventListener('livewire:load', initializeExample);
            document.addEventListener('livewire:updated', initializeExample);
            document.addEventListener('livewire:navigated', initializeExample);
        </script>
