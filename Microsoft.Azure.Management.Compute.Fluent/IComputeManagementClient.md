<Type Name="IComputeManagementClient" FullName="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient">
  <TypeSignature Language="C#" Value="public interface IComputeManagementClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IComputeManagementClient implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Interface IComputeManagementClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IComputeManagementClient = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            コンピューティングのクライアントの複合 Swagger
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AcceptLanguage">
      <MemberSignature Language="C#" Value="public string AcceptLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AcceptLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.AcceptLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property AcceptLanguage As String" />
      <MemberSignature Language="F#" Value="member this.AcceptLanguage : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.AcceptLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または応答の優先言語を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilitySets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations AvailabilitySets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations AvailabilitySets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.AvailabilitySets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilitySets As IAvailabilitySetsOperations" />
      <MemberSignature Language="F#" Value="member this.AvailabilitySets : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.AvailabilitySets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IAvailabilitySetsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            サービスのベース URI。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerServices">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations ContainerServices { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations ContainerServices" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.ContainerServices" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerServices As IContainerServicesOperations" />
      <MemberSignature Language="F#" Value="member this.ContainerServices : Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.ContainerServices" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IContainerServicesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IContainerServicesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Rest.ServiceClientCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Rest.ServiceClientCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As ServiceClientCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Rest.ServiceClientCredentials" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.ServiceClientCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Azure に接続するクライアントに必要な資格情報です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeserializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings DeserializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings DeserializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.DeserializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeserializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.DeserializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.DeserializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json に逆シリアル化の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Disks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IDisksOperations Disks { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IDisksOperations Disks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Disks" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Disks As IDisksOperations" />
      <MemberSignature Language="F#" Value="member this.Disks : Microsoft.Azure.Management.Compute.Fluent.IDisksOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Disks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IDisksOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IDisksOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateClientRequestId">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; GenerateClientRequestId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; GenerateClientRequestId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.GenerateClientRequestId" />
      <MemberSignature Language="VB.NET" Value="Public Property GenerateClientRequestId As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.GenerateClientRequestId : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.GenerateClientRequestId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            設定すると、一意の x ms-クライアントの要求 id 値を true に生成され、各要求に含まれます。 既定値は true です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Images">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IImagesOperations Images { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IImagesOperations Images" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Images" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Images As IImagesOperations" />
      <MemberSignature Language="F#" Value="member this.Images : Microsoft.Azure.Management.Compute.Fluent.IImagesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Images" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IImagesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LongRunningOperationRetryTimeout">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LongRunningOperationRetryTimeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LongRunningOperationRetryTimeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberSignature Language="VB.NET" Value="Public Property LongRunningOperationRetryTimeout As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LongRunningOperationRetryTimeout : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.LongRunningOperationRetryTimeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または長時間実行される操作の秒単位の再試行タイムアウトを設定します。 既定値は 30 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceSkus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IResourceSkusOperations ResourceSkus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IResourceSkusOperations ResourceSkus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.ResourceSkus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceSkus As IResourceSkusOperations" />
      <MemberSignature Language="F#" Value="member this.ResourceSkus : Microsoft.Azure.Management.Compute.Fluent.IResourceSkusOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.ResourceSkus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IResourceSkusOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SerializationSettings">
      <MemberSignature Language="C#" Value="public Newtonsoft.Json.JsonSerializerSettings SerializationSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Newtonsoft.Json.JsonSerializerSettings SerializationSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.SerializationSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SerializationSettings As JsonSerializerSettings" />
      <MemberSignature Language="F#" Value="member this.SerializationSettings : Newtonsoft.Json.JsonSerializerSettings" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.SerializationSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Newtonsoft.Json.JsonSerializerSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または json のシリアル化設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Snapshots">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations Snapshots { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations Snapshots" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Snapshots" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Snapshots As ISnapshotsOperations" />
      <MemberSignature Language="F#" Value="member this.Snapshots : Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Snapshots" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.ISnapshotsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ISnapshotsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionId">
      <MemberSignature Language="C#" Value="public string SubscriptionId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubscriptionId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.SubscriptionId" />
      <MemberSignature Language="VB.NET" Value="Public Property SubscriptionId As String" />
      <MemberSignature Language="F#" Value="member this.SubscriptionId : string with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.SubscriptionId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Microsoft Azure サブスクリプションを一意に識別するサブスクリプション資格情報。 サブスクリプション ID では、すべてのサービス呼び出しの URI の一部を形成します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Usage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IUsageOperations Usage { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IUsageOperations Usage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Usage" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Usage As IUsageOperations" />
      <MemberSignature Language="F#" Value="member this.Usage : Microsoft.Azure.Management.Compute.Fluent.IUsageOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.Usage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IUsageOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IUsageOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensionImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations VirtualMachineExtensionImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensionImages As IVirtualMachineExtensionImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensionImages : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineExtensionImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineExtensionImagesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations VirtualMachineExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations VirtualMachineExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineExtensions As IVirtualMachineExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineExtensions : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineExtensionsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineImages">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations VirtualMachineImages { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations VirtualMachineImages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineImages" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineImages As IVirtualMachineImagesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineImages : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineImages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineImagesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineImagesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineRunCommands">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineRunCommandsOperations VirtualMachineRunCommands" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineRunCommands" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineRunCommands As IVirtualMachineRunCommandsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineRunCommands : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineRunCommandsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineRunCommands" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineRunCommandsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachinesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachinesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachinesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetExtensions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtensionsOperations VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetExtensions As IVirtualMachineScaleSetExtensionsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetExtensions : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtensionsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSetExtensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtensionsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations VirtualMachineScaleSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSets As IVirtualMachineScaleSetsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSets : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineScaleSetsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineScaleSetVMs">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations VirtualMachineScaleSetVMs" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineScaleSetVMs As IVirtualMachineScaleSetVMsOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineScaleSetVMs : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineScaleSetVMs" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMsOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineScaleSetVMsOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachineSizes">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations VirtualMachineSizes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations VirtualMachineSizes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineSizes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachineSizes As IVirtualMachineSizesOperations" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineSizes : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations" Usage="Microsoft.Azure.Management.Compute.Fluent.IComputeManagementClient.VirtualMachineSizes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineSizesOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IVirtualMachineSizesOperations を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>