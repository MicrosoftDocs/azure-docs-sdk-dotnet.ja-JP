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
            拡張メソッドを提供します。<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /></summary>
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
        <param name="context"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> のインスタンス。</param>
        <param name="store"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</param>
        <summary>
            同期コンテキストを初期化します。
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
        <param name="context"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" /> のインスタンス。</param>
        <param name="store"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</param>
        <param name="trackingOptions">このインスタンスで有効にする必要があります traking オプション<see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />です。</param>
        <summary>
            同期コンテキストを初期化します。
            </summary>
        <returns>ときに完了するタスクを初期化が完了すると、初期化します。</returns>
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
            リモート テーブルに対して保留中のすべてのローカル操作を再生します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>