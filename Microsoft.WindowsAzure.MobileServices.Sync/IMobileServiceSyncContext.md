<Type Name="IMobileServiceSyncContext" FullName="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext">
  <TypeSignature Language="C#" Value="public interface IMobileServiceSyncContext" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMobileServiceSyncContext" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMobileServiceSyncContext" />
  <TypeSignature Language="F#" Value="type IMobileServiceSyncContext = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            リモート データベースとローカル データベースを同期する方法を提供します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Handler">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler Handler" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Handler As IMobileServiceSyncHandler" />
      <MemberSignature Language="F#" Value="member this.Handler : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Handler" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler)" />
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
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
      </Parameters>
      <Docs>
        <param name="store"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</param>
        <param name="handler"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</param>
        <summary>
            同期コンテキストを初期化します。
            </summary>
        <returns>完了するタスクを同期コンテキストが初期化されたときにします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InitializeAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task InitializeAsync (Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task InitializeAsync(class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore store, class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler handler, valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions trackingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.InitializeAsync(Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore,Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler,Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function InitializeAsync (store As IMobileServiceLocalStore, handler As IMobileServiceSyncHandler, trackingOptions As StoreTrackingOptions) As Task" />
      <MemberSignature Language="F#" Value="abstract member InitializeAsync : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore * Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler * Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.InitializeAsync (store, handler, trackingOptions)" />
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
        <Parameter Name="store" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" />
        <Parameter Name="handler" Type="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" />
        <Parameter Name="trackingOptions" Type="Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" />
      </Parameters>
      <Docs>
        <param name="store"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</param>
        <param name="handler"><see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncHandler" /> のインスタンス。</param>
        <param name="trackingOptions">A<see cref="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />値ストア操作を追跡する方法を示す、どのストア イベントが発生する影響を与えることです。</param>
        <summary>
            同期コンテキストを初期化します。
            </summary>
        <returns>完了するタスクを同期コンテキストが初期化されたときにします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsInitialized">
      <MemberSignature Language="C#" Value="public bool IsInitialized { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsInitialized" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsInitialized As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsInitialized : bool" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.IsInitialized" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            同期コンテキストが初期化されているかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PendingOperations">
      <MemberSignature Language="C#" Value="public long PendingOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 PendingOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PendingOperations As Long" />
      <MemberSignature Language="F#" Value="member this.PendingOperations : int64" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PendingOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            保留中のリモート テーブルにまだはプッシュされません操作の数を返します。
            </summary>
        <value>保留中のリモート テーブルに対する操作の数を返します。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PushAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PushAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PushAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.PushAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PushAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iMobileServiceSyncContext.PushAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />観察するトークン</param>
        <summary>
            リモート テーブルまで保留中のすべての操作をプッシュします。
            </summary>
        <returns>完了するタスクをプル操作が完了するとします。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Store">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore Store" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Store As IMobileServiceLocalStore" />
      <MemberSignature Language="F#" Value="member this.Store : Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.Store" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <see cref="T:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceLocalStore" /> のインスタンス。</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreTrackingOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions StoreTrackingOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StoreTrackingOptions As StoreTrackingOptions" />
      <MemberSignature Language="F#" Value="member this.StoreTrackingOptions : Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions" Usage="Microsoft.WindowsAzure.MobileServices.Sync.IMobileServiceSyncContext.StoreTrackingOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.MobileServices.Sync.StoreTrackingOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ストアの追跡オプションが現在有効になっていることを示すフラグです。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>