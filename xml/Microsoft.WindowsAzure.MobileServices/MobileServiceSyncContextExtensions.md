<Type Name="MobileServiceSyncContextExtensions" FullName="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions">
  <TypeSignature Language="C#" Value="public static class MobileServiceSyncContextExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MobileServiceSyncContextExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MobileServiceSyncContextExtensions" />
  <TypeSignature Language="F#" Value="type MobileServiceSyncContextExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="2bda4-101">拡張メソッドを提供します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></span><span class="sxs-lookup"><span data-stu-id="2bda4-101">Provides extension methods on <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></span></span></summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task InitializeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function InitializeAsync (context As IMobileServiceSyncContext, store As IMobileServiceLocalStore) As Task" />
      <MemberSignature Language="F#" Value="static member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.InitializeAsync (context, store)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" RefType="this" />
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="2bda4-102"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2bda4-102">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />.</span></span></param>
        <param name="store"><span data-ttu-id="2bda4-103"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2bda4-103">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <summary>
            <span data-ttu-id="2bda4-104">同期コンテキストを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2bda4-104">Initializes the sync context.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task InitializeAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function InitializeAsync (context As IMobileServiceSyncContext, store As IMobileServiceLocalStore, trackingOptions As StoreTrackingOptions) As Task" />
      <MemberSignature Language="F#" Value="static member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.InitializeAsync (context, store, trackingOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" RefType="this" />
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="trackingOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
      </Parameters>
      <Docs>
        <param name="context"><span data-ttu-id="2bda4-105"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2bda4-105">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />.</span></span></param>
        <param name="store"><span data-ttu-id="2bda4-106"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</span><span class="sxs-lookup"><span data-stu-id="2bda4-106">An instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />.</span></span></param>
        <param name="trackingOptions"><span data-ttu-id="2bda4-107">このインスタンスで有効にする必要があります traking オプション<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />です。</span><span class="sxs-lookup"><span data-stu-id="2bda4-107">The traking options that should be enabled on this instance of <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />.</span></span></param>
        <summary>
            <span data-ttu-id="2bda4-108">同期コンテキストを初期化します。</span><span class="sxs-lookup"><span data-stu-id="2bda4-108">Initializes the sync context.</span></span>
            </summary>
        <returns><span data-ttu-id="2bda4-109">ときに完了するタスクを初期化が完了すると、初期化します。</span><span class="sxs-lookup"><span data-stu-id="2bda4-109">A task that completes when the initialization when initialization has finished.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task PushAsync (this Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task PushAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.PushAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PushAsync (context As IMobileServiceSyncContext) As Task" />
      <MemberSignature Language="F#" Value="static member PushAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext -&gt; System.Threading.Tasks.Task" Usage="Microsoft.WindowsAzure.MobileServices.MobileServiceSyncContextExtensions.PushAsync context" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="context" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" RefType="this" />
      </Parameters>
      <Docs>
        <param name="context">To be added.</param>
        <summary>
            <span data-ttu-id="2bda4-110">リモート テーブルに対して保留中のすべてのローカル操作を再生します。</span><span class="sxs-lookup"><span data-stu-id="2bda4-110">Replays all pending local operations against the remote tables.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>