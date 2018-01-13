<Type Name="FabricClient+ServiceManagementClient" FullName="System.Fabric.FabricClient+ServiceManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ServiceManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceManagementClient = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>管理する、サービスの有効化を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceAsync (description As ServiceDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>サービスの構成。 A<see cref="T:System.Fabric.Description.ServiceDescription" />すべてのサービスを作成するために必要な情報が含まれています。</para>
        </param>
        <summary>
          <para>指定された説明とサービスをインスタンス化します。</para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="description" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription serviceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription serviceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync (serviceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para>サービスの構成。 A<see cref="T:System.Fabric.Description.ServiceDescription" />すべてのサービスを作成するために必要な情報が含まれています。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定された説明とサービスをインスタンス化します。 これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="serviceDescription" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync serviceFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para>アプリケーション マニフェストで指定されたサービス テンプレートから作成するサービスをについて説明します。</para>
        </param>
        <summary>
          <para>アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (serviceFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para>アプリケーション マニフェストで指定されたサービス テンプレートから作成するサービスをについて説明します。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスが作成されるアプリケーションのサービス ファブリック名。</para>
        </param>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="serviceTypeName">
          <para>サービスの種類の名前。 サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</para>
        </param>
        <param name="initializationData">
          <para>初期化データでは、サービスの作成者によって提供されるカスタム データを表します。 Service Fabric は、このデータを解析できません。 このデータはすべてのインスタンスまたは内のレプリカで利用可能になります<see cref="T:System.Fabric.StatefulServiceContext" />または<see cref="T:System.Fabric.StatelessServiceContext" />です。            
            これは、サービスを作成した後に変更できません。 
            </para>
        </param>
        <summary>
          <para>アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。</para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><paramref name="applicationName" /> または <paramref name="serviceName" /> が null の場合。</exception>
        <exception cref="T:System.ArgumentException">ときに<paramref name="serviceTypeName" />が null またはホワイト スペースです。</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>サービスが作成されるアプリケーションのサービス ファブリック名。</para>
        </param>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="serviceTypeName">
          <para>サービスの種類の名前。 サービス マニフェストで指定された ServiceTypeName と同じにする必要があります。</para>
        </param>
        <param name="initializationData">
          <para>初期化データでは、サービスの作成者によって提供されるカスタム データを表します。 Service Fabric は、このデータを解析できません。 このデータはすべてのインスタンスまたは内のレプリカで利用可能になります<see cref="T:System.Fabric.StatefulServiceContext" />または<see cref="T:System.Fabric.StatelessServiceContext" />です。            
            これは、サービスを作成した後に変更できません。 
            </para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>アプリケーション マニフェストで指定されたテンプレートからサービスをインスタンス化します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>インスタンス化されたサービスです。</para>
        </returns>
        <remarks>
          <para>既に存在しない場合、Service Fabric 名は暗黙的に作成されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: サービス テンプレートが存在しません。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>要求がタイムアウトしましたが許可されている処理のため、システムによって。</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>タイムアウト期限が切れている可能性があります許可されている処理のため、システムによって前に、要求が取り消されました。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><paramref name="applicationName" /> または <paramref name="serviceName" /> が null の場合。</exception>
        <exception cref="T:System.ArgumentException">ときに<paramref name="serviceTypeName" />が null またはホワイト スペースです。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync deleteServiceDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para>削除するサービスの説明です。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスを削除します。</para>
        </summary>
        <returns>
          <para>削除されたサービス インスタンス。</para>
        </returns>
        <remarks>
          <para>サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</para>
          <para>強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="deleteServiceDescription" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスを削除します。</para>
        </summary>
        <returns>
          <para>削除されたサービス インスタンス。</para>
        </returns>
        <remarks>
          <para>サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="serviceName" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (deleteServiceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para>削除するサービスの説明です。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスを削除します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>削除されたサービス インスタンス。</para>
        </returns>
        <remarks>
          <para>サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</para>
          <para>強制的な削除の呼び出しは、強制的な 1 つを継続的に通常の削除を変換できます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="deleteServiceDescription" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスを削除します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>削除されたサービス インスタンス。</para>
        </returns>
        <remarks>
          <para>サービス ファブリック名は暗黙的になり、アプリケーションが Service Fabric である場合は削除を再帰的に管理されます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="serviceName" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceDescriptionAsync (serviceName As Uri) As Task(Of ServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスのサービスの説明を取得します。</para>
        </summary>
        <returns>
          <para>指定されたサービス インスタンスのサービスの説明。</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
          <para>
            <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />名前がサービスに関連付けられているかどうかを判断する最も効率的な方法です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="serviceName" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。 </para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定されたサービス インスタンスのサービスの説明を取得します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>指定されたサービス インスタンスのサービスの説明。</para>
        </returns>
        <remarks>
          <para>
            <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />名前がサービスに関連付けられているかどうかを判断する最も効率的な方法です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">ときに<paramref name="serviceName" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestAsync (applicationTypeName As String, applicationTypeVersion As String, serviceManifestName As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>プロビジョニング済みのアプリケーション マニフェストの名前。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>プロビジョニング済みのアプリケーション マニフェストのバージョン。</para>
        </param>
        <param name="serviceManifestName">
          <para>アプリケーション マニフェストで参照されたサービス マニフェストの名前。</para>
        </param>
        <summary>
          <para>指定したアプリケーションの種類名およびアプリケーション タイプのバージョンでプロビジョニングされたサービス マニフェスト ドキュメントを取得します。</para>
        </summary>
        <returns>
          <para>プロビジョニングされたサービス マニフェストのドキュメント。</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>プロビジョニング済みのアプリケーション マニフェストの名前。</para>
        </param>
        <param name="applicationTypeVersion">
          <para>プロビジョニング済みのアプリケーション マニフェストのバージョン。</para>
        </param>
        <param name="serviceManifestName">
          <para>アプリケーション マニフェストで参照されたサービス マニフェストの名前。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したアプリケーションの種類名およびアプリケーション タイプのバージョンでプロビジョニングされたサービス マニフェスト ドキュメントを取得します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>プロビジョニングされたサービス マニフェスト ドキュメント</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="applicationTypeName" />または<paramref name="applicationTypeVersion" />または<paramref name="serviceManifestName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServiceNotificationFilterAsync (description As ServiceNotificationFilterDescription) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>どのサービス エンドポイントの変更イベントを決定する説明を使用してこのクライアントに配信する必要があります、<see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />イベント。</para>
        </param>
        <summary>
          <para>登録、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。 タスクの結果は、登録されているに対応する ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />を使用して、同じフィルターの登録解除に使用できる<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />です。</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="description" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>どのサービス エンドポイントの変更イベントを決定する説明を使用してこのクライアントに配信する必要があります、<see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />イベント。</para>
        </param>
        <param name="timeout">
          <para>前に要求の処理時間の最大値が許可されている<see cref="T:System.TimeoutException" />がスローされます。</para>
        </param>
        <param name="cancellationToken">
          <para>将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>登録、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。 タスクの結果は、登録されているに対応する ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />を使用して、同じフィルターの登録解除に使用できる<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />です。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="description" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="callback">
          <para>この関数は、通知が到着したときに呼び出されます。</para>
        </param>
        <summary>
          <para>この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</para>
        </summary>
        <returns>
          <para>サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</para>
        </returns>
        <remarks>
          <para>通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。 このオーバー ロードでは、シングルトンのパーティション分割されているサービス インスタンスが使用されます。 返される Int64 は、登録のコールバック ハンドル識別子です。</para>
          <para>通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。 こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, long partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Int64,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As Long, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * int64 * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="callback">
          <para>この関数は、通知が到着したときに呼び出されます。</para>
        </param>
        <summary>
          <para>この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</para>
        </summary>
        <returns>
          <para>サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</para>
        </returns>
        <remarks>
          <para>通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。 このオーバー ロードでは、パーティション分割されている UniformInt64Range サービス インスタンスが使用されます。 返される Int64 は、登録のコールバック ハンドル識別子です。</para>
          <para>通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。 こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, string partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, string partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.String,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As String, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * string * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="callback">
          <para>この関数は、通知が到着したときに呼び出されます。</para>
        </param>
        <summary>
          <para>この API は非推奨<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />代わりにします。</para>
        </summary>
        <returns>
          <para>サービス パーティションのアクセシビリティ情報が変更されたときに発生するハンドラー。</para>
        </returns>
        <remarks>
          <para>通知は、パーティションのエンドポイントまたは情報の更新中に発生した例外での変更が含まれます。 このオーバー ロードでは、名前付きのパーティション分割されているサービス インスタンスが使用されます。 返される Int64 は、登録のコールバック ハンドル識別子です。</para>
          <para>通知では、時間がありますが、サービス アドレスの変更またはコードのサービス パーティションに関連するアドレス解決エラーを各ユーザーのコードに通知を配信するメカニズムが発生するの関心です。 こうするたびに、現在の解決ではなく<see cref="T:System.Fabric.ResolvedServicePartition" />なりますの更新プログラムが登録古くなって 場合。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">場合<paramref name="serviceName" />または<paramref name="callback" />が null です。</exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="partitionKey" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <summary>
          <para>ノード上で実行されているサービス レプリカを削除します。</para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。 </para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long, forceRemove As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <param name="forceRemove">
          <para>正常にその状態をクリーンアップして閉じるできる必要があります、レプリカに指定するかどうかを指定します</para>
        </param>
        <summary>
          <para>ノード上で実行されているサービス レプリカを削除します。</para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。 </para>
          <para>ForceRemove フラグが設定されている場合、このような営業案件は指定されませんでした。 Service Fabric がそのレプリカのホストを終了し、そのレプリカのすべての永続化された状態がリークします。 </para>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</para>
          <para>さらに、forceRemove フラグでは、同じプロセスでホストされているその他のすべてのレプリカに影響します。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>ノード上で実行されているサービス レプリカを削除します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。 </para>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <param name="forceRemove">
          <para>正常にその状態をクリーンアップして閉じるできる必要があります、レプリカに指定するかどうかを指定します</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>ノード上で実行されているサービス レプリカを削除します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>この API を使用して、実行中のレプリカ可能性クリーンアップするには、状態、正常にシャット ダウンをします。 </para>
          <para>ForceRemove フラグが設定されている場合、このような営業案件は指定されませんでした。 Service Fabric がそのレプリカのホストを終了し、そのレプリカのすべての永続化された状態がリークします。 </para>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフルなサービスのデータ損失につながることができます。</para>
          <para>さらに、forceRemove フラグでは、同じプロセスでホストされているその他のすべてのレプリカに影響します。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para><see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />が返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="previousResult">
          <para>前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>API の解像度を苦情に基づいています。</para>
          <para>このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。 </para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。 </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="previousResult">
          <para>前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。 </para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="previousResult">
          <para>以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>このメソッドは、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>
            <paramref name="previousResult" />引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。ResolveServicePartition なしで呼び出される、<paramref name="previousResult" />引数または<paramref name="previousResult" />引数を null に設定します。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムは常に返します、最も近い<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>以前<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>
            <see cref="T:System.Threading.CancellationToken" />操作を確認します。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービス インスタンスのサービス ファブリック名。</para>
        </param>
        <param name="partitionKey">
          <para>サービス パーティションのパーティション キーです。</para>
        </param>
        <param name="previousResult">
          <para>前の<see cref="T:System.Fabric.ResolvedServicePartition" />ユーザーと認識しているサービスのパーティションは古いのです。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定したサービス パーティションをリッスンするエンドポイントのセットをシステムに照会します。</para>
        </summary>
        <returns>
          <para>指定したサービス パーティションがリッスンしている一連のエンドポイント。</para>
        </returns>
        <remarks>
          <para>これは、準拠しているベース解決 API です。</para>
          <para>返されます、<see cref="T:System.Fabric.ResolvedServicePartition" />指定したサービス パーティション用です。 このオーバー ロードを使用すると、システムを返しますより最新<see cref="T:System.Fabric.ResolvedServicePartition" />"previousResult"の引数がある場合よりもします。</para>
          <para>PreviousResult 引数により、"これは、このサービス パーティションのエンドポイントの前の一覧ですを言うようにユーザーに。 エンドポイントを試行し、それらが古くなっていないと思います。 返す me このセットの最新バージョンです。" この場合、システムより最新を返すを試みます。<see cref="T:System.Fabric.ResolvedServicePartition" />最も効率的な方法でします。 新しいバージョンが見つからない場合、<see cref="T:System.Fabric.ResolvedServicePartition" />同じバージョンが返されます。PreviousResult 引数または previousResult 引数を null に設定がない ResolveServicePartition を呼び出すことができます。 システムがの最も近いコピーを返すように必要な前提条件が指定されていない、<see cref="T:System.Fabric.ResolvedServicePartition" />サービス パーティション用です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <summary>
          <para>ノード上で実行されている永続化されたサービスのサービス レプリカを再起動します。</para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフル サービスの可用性の損失につながる場合があります。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />レプリカは、ステートフルな永続化されたサービスに属していないかどうかが返されます。 のみステートフルな永続化されたレプリカを再起動することができます。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>ノード名。</para>
        </param>
        <param name="partitionId">
          <para>パーティションの識別子です。</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>インスタンス識別子。</para>
        </param>
        <param name="timeout">
          <para>返す前に続行するには、この操作により、最長時間を定義する timespan、<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para>操作を確認する省略可能なキャンセル トークン。 操作を取り消す必要がある通知を送信するために使用します。 キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>ノード上で実行されている永続化されたサービスのサービス レプリカを再起動します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>要求の受信確認を表すタスク。</para>
        </returns>
        <remarks>
          <para>警告: この API を使用する場合に実行される安全性チェックはありません。 この API の不適切な使用は、ステートフル サービスの可用性の損失につながる場合があります。</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                参照してください<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />レプリカまたはインスタンスの id が、ノードで実行されていないかどうかが返されます。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />レプリカまたはインスタンスの id の再起動または無効な状態であるために、この時点で削除できないかどうかに返されます。 レプリカは既に閉じられている処理を行ってです。</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />レプリカは、ステートフルな永続化されたサービスに属していないかどうかが返されます。 のみステートフルな永続化されたレプリカを再起動することができます。</para>
          <para>
                関連項目<see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" />FabricClient の一般的な障害を処理するためです。</para>
        </exception>
        <exception cref="T:System.ArgumentException">場合<paramref name="nodeName" />が null または空です。</exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceNotificationFilterMatched">
      <MemberSignature Language="C#" Value="public event EventHandler ServiceNotificationFilterMatched;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ServiceNotificationFilterMatched" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />
      <MemberSignature Language="VB.NET" Value="Public Event ServiceNotificationFilterMatched As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ServiceNotificationFilterMatched : EventHandler " Usage="member this.ServiceNotificationFilterMatched : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>いつ発生するか、<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって以前登録<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />システムで、サービスのエンドポイントの変更と一致します。</para>
        </summary>
        <remarks>
            イベント引数の型が<see cref="T:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationEventArgs" />です。
            </remarks>
        <example>
            次の例では、登録し、サービスの通知を処理する方法を示します。
            <code language="cs">
            namespace ServiceNotificationsExample
            {
                class Program
                {
                    static void Main(string[] args)
                    {
                        var client = new FabricClient(new string[] { "[cluster_endpoint]:[client_port]" });
            
                        var filter = new ServiceNotificationFilterDescription()
                        {
                            Name = new Uri("fabric:/my_application"),
                            MatchNamePrefix = true,
                        };
            
                        client.ServiceManager.ServiceNotificationFilterMatched += (s, e) =&gt; OnNotification(e);
            
                        var filterId = client.ServiceManager.RegisterServiceNotificationFilterAsync(filter).Result;
            
                        Console.WriteLine(
                            "Registered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
            
                        Console.ReadLine();
            
                        client.ServiceManager.UnregisterServiceNotificationFilterAsync(filterId).Wait();
            
                        Console.WriteLine(
                            "Unregistered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
                    }
            
                    private static void OnNotification(EventArgs e)
                    {
                        var castedEventArgs = (FabricClient.ServiceManagementClient.ServiceNotificationEventArgs)e;
            
                        var notification = castedEventArgs.Notification;
            
                        Console.WriteLine(
                            "[{0}] received notification for service '{1}'",
                            DateTime.UtcNow,
                            notification.ServiceName);
                    }
                }
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterServiceNotificationFilterAsync (filterId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync filterId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para>以前に登録済みの ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />から返された<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</para>
        </param>
        <summary>
          <para>以前に登録されてから登録解除<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</para>
        </returns>
        <remarks>
          <para>クライアント自体はすべて使用できなく個々 のフィルターの登録を解除する必要はありません<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって登録されているオブジェクト、<see cref="T:System.Fabric.FabricClient" />されません自動的に登録されているクライアントが破棄されるときにします。</para>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync (filterId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para>以前に登録済みの ID<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />から返された<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />です。</para>
        </param>
        <param name="timeout">
          <para>前に要求の処理時間の最大値が許可されている<see cref="T:System.TimeoutException" />がスローされます。</para>
        </param>
        <param name="cancellationToken">
          <para>将来使用するために予約されています。</para>
        </param>
        <summary>
          <para>以前に登録されてから登録解除<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />です。</para>
        </summary>
        <returns>
          <para>A<see cref="T:System.Threading.Tasks.Task" />非同期操作を表すです。</para>
        </returns>
        <remarks>
            クライアント自体はすべて使用できなく個々 のフィルターの登録を解除する必要はありません<see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />によって登録されているオブジェクト、<see cref="T:System.Fabric.FabricClient" />されません自動的に登録されているクライアントが破棄されるときにします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public void UnregisterServicePartitionResolutionChangeHandler (long callbackHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnregisterServicePartitionResolutionChangeHandler(int64 callbackHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServicePartitionResolutionChangeHandler(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UnregisterServicePartitionResolutionChangeHandler (callbackHandle As Long)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServicePartitionResolutionChangeHandler : int64 -&gt; unit" Usage="serviceManagementClient.UnregisterServicePartitionResolutionChangeHandler callbackHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackHandle" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="callbackHandle">
          <para>削除される callbackHandle 識別子です。 これは、によって返される、<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />呼び出します。</para>
        </param>
        <summary>
          <para>以前に登録されている変更ハンドラーの登録解除<see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />です。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceAsync (name As Uri, updateDescription As ServiceUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, updateDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>更新中、サービスの URI 名です。</para>
        </param>
        <param name="updateDescription">
          <para><see cref="T:System.Fabric.Description.ServiceUpdateDescription" />サービスの更新された構成を指定します。</para>
        </param>
        <summary>
          <para>指定された説明では、サービスを更新します。</para>
        </summary>
        <returns>
          <para>更新されたサービスです。</para>
        </returns>
        <remarks>
          <para>既定のタイムアウトは、システムを返す前に続行するには、この操作を許可 1 分<see cref="T:System.TimeoutException" />です。 </para>
          <para>注: を安全に両方を増やすには、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />と<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />最初を増やす、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />を作成して向上し、さらにレプリカを待機し、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。
            破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><paramref name="name" /> または <paramref name="updateDescription" /> が null の場合。</exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, serviceUpdateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="serviceUpdateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>更新中、サービスの URI 名です。</para>
        </param>
        <param name="serviceUpdateDescription">
          <para><see cref="T:System.Fabric.Description.ServiceUpdateDescription" />サービスの更新された構成を指定します。</para>
        </param>
        <param name="timeout">
          <para>システムで返す前に続行するには、この操作は許可最長時間<see cref="T:System.TimeoutException" />です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</para>
        </param>
        <summary>
          <para>指定された説明では、サービスを更新します。
            これは、システムを返す前に続行するには、この操作を許可する時間の最大タイムアウト間隔でも受け取る<see cref="T:System.TimeoutException" />し、操作を観察するキャンセル トークン。 
            </para>
        </summary>
        <returns>
          <para>更新されたサービスです。</para>
        </returns>
        <remarks>
          <para>注: を安全に両方を増やすには、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" />と<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />最初を増やす、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" />を作成して向上し、さらにレプリカを待機し、<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。
            破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
        <exception cref="T:System.ArgumentNullException"><paramref name="name" /> または <paramref name="serviceUpdateDescription" /> が null の場合。</exception>
      </Docs>
    </Member>
  </Members>
</Type>