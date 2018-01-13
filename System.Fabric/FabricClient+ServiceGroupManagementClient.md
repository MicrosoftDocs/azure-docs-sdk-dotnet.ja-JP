<Type Name="FabricClient+ServiceGroupManagementClient" FullName="System.Fabric.FabricClient+ServiceGroupManagementClient">
  <TypeSignature Language="C#" Value="public class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit FabricClient/ServiceGroupManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceGroupManagementClient = class" />
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
      <para>により、クライアント側の作成、削除、およびクラスター内のサービス グループの検査と同じように、<see cref="T:System.Fabric.FabricClient.ServiceManagementClient" />正規サービス。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupAsync (description As ServiceGroupDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:System.Fabric.Description.ServiceGroupDescription" />グループとそのメンバーをについて説明します。</param>
        <summary>
            非同期的にグループを作成、サービスから、指定された<see cref="T:System.Fabric.Description.ServiceGroupDescription" />です。
            </summary>
        <returns>非同期サービス グループの作成操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description"><see cref="T:System.Fabric.Description.ServiceGroupDescription" />グループとそのメンバーをについて説明します。</param>
        <param name="timeout">Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルが推奨でが取り消された場合でもは、操作を完了も可能性がありますに注意してください。</param>
        <summary>
            サービス グループを非同期に作成、特定<see cref="T:System.Fabric.Description.ServiceGroupDescription" />で指定したタイムアウトと<see cref="T:System.Threading.CancellationToken" />です。
            </summary>
        <returns>非同期サービス グループの作成操作を表すタスク。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync serviceGroupFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para>アプリケーション マニフェストで指定されたサービスのグループ テンプレートから作成される、サービスのグループについて説明します。</para>
        </param>
        <summary>
          <para>現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</para>
        </summary>
        <returns>
          <para>非同期サービス グループの作成操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (serviceGroupFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para>アプリケーション マニフェストで指定されたサービスのグループ テンプレートから作成される、サービスのグループについて説明します。</para>
        </param>
        <param name="timeout">
          <para>最大許容時間、操作を完了するまで、TimeoutException がスローされます。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</para>
        </summary>
        <returns>
          <para>非同期サービス グループの作成操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
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
          <para>サービス グループのアプリケーション名</para>
        </param>
        <param name="serviceName">
          <para>サービス グループのサービス名</para>
        </param>
        <param name="serviceTypeName">
          <para>サービス グループのサービスの種類名</para>
        </param>
        <param name="initializationData">
          <para>サービス グループのインスタンスに渡す初期化データ</para>
        </param>
        <summary>
          <para>現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</para>
        </summary>
        <returns>
          <para>非同期サービス グループの作成操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
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
          <para>サービス グループのアプリケーション名</para>
        </param>
        <param name="serviceName">
          <para>サービス グループのサービス名</para>
        </param>
        <param name="serviceTypeName">
          <para>サービス グループのサービスの種類名</para>
        </param>
        <param name="initializationData">
          <para>サービス グループのインスタンスに渡す初期化データ</para>
        </param>
        <param name="timeout">
          <para>最大許容時間、操作を完了するまで、TimeoutException がスローされます。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>現在のアプリケーション マニフェストであらかじめ定義されているサービス グループ テンプレートからサービス グループを作成します。</para>
        </summary>
        <returns>
          <para>非同期サービス グループの作成操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceGroupAsync (serviceGroupName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>削除するサービス グループの名前。</para>
        </param>
        <summary>
          <para>非同期的に、指定されたサービスのグループを削除します。</para>
        </summary>
        <returns>
          <para>非同期サービス グループを表すタスクでは、操作を削除します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>削除するサービス グループの名前。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認するオブジェクト。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>指定したタイムアウトで指定されたサービスのグループを非同期に削除し、<see cref="T:System.Threading.CancellationToken" />です。</para>
        </summary>
        <returns>
          <para>非同期サービス グループを表すタスクでは、操作を削除します。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupDescriptionAsync (serviceGroupName As Uri) As Task(Of ServiceGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>サービスの名前でグループ化が<see cref="T:System.Fabric.Description.ServiceGroupDescription" />フェッチする必要があります。</para>
        </param>
        <summary>
          <para>非同期的にフェッチ、<see cref="T:System.Fabric.Description.ServiceGroupDescription" />存在する場合、指定したサービス グループにします。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>サービスの名前でグループ化が<see cref="T:System.Fabric.Description.ServiceGroupDescription" />フェッチする必要があります。</para>
        </param>
        <param name="timeout">
          <para>Service Fabric は、タイムアウト例外を返す前に続行するには、この操作を許可する時間の最大量を定義する Timespan です。</para>
        </param>
        <param name="cancellationToken">
          <para><see cref="T:System.Threading.CancellationToken" />操作を確認することです。  操作を取り消す必要がある通知を送信するために使用します。  キャンセルは希望して取り消される場合でもは、操作を完了も可能性がありますに注意してください。</para>
        </param>
        <summary>
          <para>非同期的にフェッチ、 <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> 、指定したサービス グループを指定したタイムアウトで、存在する場合と<see cref="T:System.Threading.CancellationToken" />です。</para>
        </summary>
        <returns>
          <para>非同期操作を表すタスク。</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para><see cref="T:System.Fabric.FabricClient" />オブジェクトが closed 状態にします。 破棄、<see cref="T:System.Fabric.FabricClient" />オブジェクトを使用しているし、新しいインスタンスを作成する<see cref="T:System.Fabric.FabricClient" />オブジェクト。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceGroupAsync (name As Uri, updateDescription As ServiceGroupUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription)" />
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
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name">更新中のサービス グループの URI 名です。</param>
        <param name="updateDescription"><see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" />サービス グループの更新された構成を指定します。</param>
        <summary>
            指定された説明を持つサービス グループを非同期に更新します。
            </summary>
        <returns>非同期サービス グループを表すタスクでは、操作を更新します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription, timeout, cancellationToken)" />
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
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">更新中、サービスの URI 名です。</param>
        <param name="updateDescription"><see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" />サービスの更新された構成を指定します。</param>
        <param name="timeout">システムで返す前に実行するには、この API は許可最長時間<see cref="T:System.TimeoutException" />です。</param>
        <param name="cancellationToken"><see cref="T:System.Threading.CancellationToken" />操作を確認することです。 操作を取り消す必要がある通知を伝達するために使用します。</param>
        <summary>
            指定された説明を持つサービス グループを非同期に更新します。
            </summary>
        <returns>非同期サービス グループを表すタスクでは、操作を更新します。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>