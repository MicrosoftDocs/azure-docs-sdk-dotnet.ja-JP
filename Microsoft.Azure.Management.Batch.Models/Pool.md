<Type Name="Pool" FullName="Microsoft.Azure.Management.Batch.Models.Pool">
  <TypeSignature Language="C#" Value="public class Pool : Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Pool extends Microsoft.Azure.Management.Batch.Models.ProxyResource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.Pool" />
  <TypeSignature Language="VB.NET" Value="Public Class Pool&#xA;Inherits ProxyResource" />
  <TypeSignature Language="F#" Value="type Pool = class&#xA;    inherit ProxyResource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.Batch.Models.ProxyResource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            プールに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            プール クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Pool (string id = null, string name = null, string type = null, string etag = null, string displayName = null, Nullable&lt;DateTime&gt; lastModified = null, Nullable&lt;DateTime&gt; creationTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, string vmSize = null, Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration = null, Nullable&lt;int&gt; currentDedicatedNodes = null, Nullable&lt;int&gt; currentLowPriorityNodes = null, Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun = null, Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication = null, Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration = null, Nullable&lt;int&gt; maxTasksPerNode = null, Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata = null, Microsoft.Azure.Management.Batch.Models.StartTask startTask = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages = null, System.Collections.Generic.IList&lt;string&gt; applicationLicenses = null, Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string etag, string displayName, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; lastModified, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, string vmSize, class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration deploymentConfiguration, valuetype System.Nullable`1&lt;int32&gt; currentDedicatedNodes, valuetype System.Nullable`1&lt;int32&gt; currentLowPriorityNodes, class Microsoft.Azure.Management.Batch.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.Batch.Models.AutoScaleRun autoScaleRun, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; interNodeCommunication, class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration networkConfiguration, valuetype System.Nullable`1&lt;int32&gt; maxTasksPerNode, class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy taskSchedulingPolicy, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; userAccounts, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; metadata, class Microsoft.Azure.Management.Batch.Models.StartTask startTask, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; certificates, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; applicationPackages, class System.Collections.Generic.IList`1&lt;string&gt; applicationLicenses, class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus resizeOperationStatus) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.#ctor(System.String,System.String,System.String,System.String,System.String,System.Nullable{System.DateTime},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.PoolProvisioningState},System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.Batch.Models.AllocationState},System.Nullable{System.DateTime},System.String,Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration,System.Nullable{System.Int32},System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.ScaleSettings,Microsoft.Azure.Management.Batch.Models.AutoScaleRun,System.Nullable{Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState},Microsoft.Azure.Management.Batch.Models.NetworkConfiguration,System.Nullable{System.Int32},Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.UserAccount},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.MetadataItem},Microsoft.Azure.Management.Batch.Models.StartTask,System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.CertificateReference},System.Collections.Generic.IList{Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference},System.Collections.Generic.IList{System.String},Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.Pool : string * string * string * string * string * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * string * Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration * Nullable&lt;int&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.ScaleSettings * Microsoft.Azure.Management.Batch.Models.AutoScaleRun * Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; * Microsoft.Azure.Management.Batch.Models.NetworkConfiguration * Nullable&lt;int&gt; * Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; * Microsoft.Azure.Management.Batch.Models.StartTask * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; * System.Collections.Generic.IList&lt;string&gt; * Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus -&gt; Microsoft.Azure.Management.Batch.Models.Pool" Usage="new Microsoft.Azure.Management.Batch.Models.Pool (id, name, type, etag, displayName, lastModified, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, vmSize, deploymentConfiguration, currentDedicatedNodes, currentLowPriorityNodes, scaleSettings, autoScaleRun, interNodeCommunication, networkConfiguration, maxTasksPerNode, taskSchedulingPolicy, userAccounts, metadata, startTask, certificates, applicationPackages, applicationLicenses, resizeOperationStatus)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="displayName" Type="System.String" />
        <Parameter Name="lastModified" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="deploymentConfiguration" Type="Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration" />
        <Parameter Name="currentDedicatedNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentLowPriorityNodes" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.Batch.Models.ScaleSettings" />
        <Parameter Name="autoScaleRun" Type="Microsoft.Azure.Management.Batch.Models.AutoScaleRun" />
        <Parameter Name="interNodeCommunication" Type="System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;" />
        <Parameter Name="networkConfiguration" Type="Microsoft.Azure.Management.Batch.Models.NetworkConfiguration" />
        <Parameter Name="maxTasksPerNode" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="taskSchedulingPolicy" Type="Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy" />
        <Parameter Name="userAccounts" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;" />
        <Parameter Name="startTask" Type="Microsoft.Azure.Management.Batch.Models.StartTask" />
        <Parameter Name="certificates" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;" />
        <Parameter Name="applicationPackages" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;" />
        <Parameter Name="applicationLicenses" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
        <Parameter Name="resizeOperationStatus" Type="Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID。</param>
        <param name="name">リソースの名前。</param>
        <param name="type">リソースの型。</param>
        <param name="etag">同時実行ステートメントの使用、リソースの ETag。</param>
        <param name="displayName">プールの表示名。</param>
        <param name="lastModified">最終更新時刻プールをします。</param>
        <param name="creationTime">プールの作成時間。</param>
        <param name="provisioningState">プールの現在の状態。</param>
        <param name="provisioningStateTransitionTime">現在の状態、プールになった時刻。</param>
        <param name="allocationState">プールのサイズを変更するかどうか。</param>
        <param name="allocationStateTransitionTime">現在の割り当て状態、プールになった時刻。</param>
        <param name="vmSize">プール内の仮想マシンのサイズ。 プール内のすべての Vm は、同じサイズです。</param>
        <param name="deploymentConfiguration">このプロパティは、プールのノードがある方法について説明します - クラウド サービスまたは仮想マシンを使用して展開します。</param>
        <param name="currentDedicatedNodes">現在、プール内の計算ノードの数。</param>
        <param name="currentLowPriorityNodes">低優先度の数は、現在、プール内のノードを計算します。</param>
        <param name="scaleSettings">プール内のノードの数を構成する設定です。</param>
        <param name="autoScaleRun">結果と自動スケール式の前回の実行からのエラーです。</param>
        <param name="interNodeCommunication">かどうか、プールは、ノード間の直接通信を許可します。</param>
        <param name="networkConfiguration">プールのネットワーク構成。</param>
        <param name="maxTasksPerNode">プール内の単一コンピューティング ノードで同時に実行できるタスクの最大数。</param>
        <param name="taskSchedulingPolicy">どのタスクはプール内のコンピューティング ノード間で分散されます。</param>
        <param name="userAccounts">プール内の各ノード上に作成されるユーザー アカウントの一覧です。</param>
        <param name="metadata">メタデータとしてプールに関連付けられている名前と値のペアの一覧。</param>
        <param name="startTask">各コンピューティング ノードで、プールに参加を実行する指定されたタスク。</param>
        <param name="certificates">プール内の各コンピューティング ノードにインストールされている証明書の一覧です。</param>
        <param name="applicationPackages">プール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧。</param>
        <param name="applicationLicenses">アプリケーションの一覧のライセンスは、バッチ サービスは、プール内の各コンピューティング ノードで使用できるようにします。</param>
        <param name="resizeOperationStatus">現在または最近完了したサイズ変更操作に関する詳細情報が含まれています。</param>
        <summary>
            プール クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             プールのサイズを変更するかどうかを取得します。
             </summary>
        <value>To be added.</value>
        <remarks>
             値は次のとおりです。
            
             steady - プールがないをサイズ変更します。 進行中のプール内のノードの数を変更することはありません。 プールは、専用のノードの数を変更するプールの操作が実行されているされないときとが作成されるときに、この状態を入力します。
             このサイズを変更するには、プールのサイズを変更します。つまり、コンピューティング ノードの中に追加またはプールから削除します。
             停止中 - プールのサイズ変更が、ユーザーは、サイズ変更を停止することを要求したが停止要求がまだ完了していません。 使用可能な値が含まれます: '点灯'、'サイズを変更する'、'停止'
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プールが現在の割り当て状態を入力するされた時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationLicenses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ApplicationLicenses { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ApplicationLicenses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationLicenses As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ApplicationLicenses : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationLicenses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationLicenses")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアプリケーションのライセンスの一覧をバッチ サービスは、プール内の各コンピューティング ノードで使用できるように設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            アプリケーションのライセンスの一覧は、使用できる Batch サービス アプリケーションのライセンスのサブセットである必要があります。 これはサポートされていない要求されるライセンスと、プールの作成は失敗します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationPackages">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; ApplicationPackages" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationPackages As IList(Of ApplicationPackageReference)" />
      <MemberSignature Language="F#" Value="member this.ApplicationPackages : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ApplicationPackages" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.applicationPackages")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.ApplicationPackageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされているアプリケーション パッケージの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            アプリケーション パッケージへの変更は、プールに参加するすべての新しいコンピューティング ノードに影響するが、コンピューティング ノードを再起動または再イメージ化されるまで、プールに既に存在するには影響しません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoScaleRun">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.AutoScaleRun AutoScaleRun" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoScaleRun As AutoScaleRun" />
      <MemberSignature Language="F#" Value="member this.AutoScaleRun : Microsoft.Azure.Management.Batch.Models.AutoScaleRun" Usage="Microsoft.Azure.Management.Batch.Models.Pool.AutoScaleRun" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.autoScaleRun")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.AutoScaleRun</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            自動スケール式の前回の実行からの結果とエラーを取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            このプロパティが専用場合、プールは自動的にスケーリング、つまり autoScaleSettings が使用されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Certificates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; Certificates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberSignature Language="VB.NET" Value="Public Property Certificates As IList(Of CertificateReference)" />
      <MemberSignature Language="F#" Value="member this.Certificates : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Certificates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.certificates")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.CertificateReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各コンピューティング ノードにインストールされている証明書の一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            Windows では、ノードを計算するため、バッチ サービスは、場所と指定された証明書ストアに証明書をインストールします。 Linux 計算ノードでは、証明書は、タスクの作業ディレクトリと変数 AZ_BATCH_CERTIFICATES_DIR がこの場所にクエリするタスクに指定された環境の内部ディレクトリに保存されます。 'RemoteUser' の可視性を持つ証明書は、'certs' ディレクトリは、ユーザーのホーム ディレクトリに作成 (など/home/{ユーザー名}/certs) および証明書はそのディレクトリに配置します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プールの作成時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentDedicatedNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentDedicatedNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentDedicatedNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentDedicatedNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentDedicatedNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentDedicatedNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentDedicatedNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            現在、プール内のコンピューティング ノードの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentLowPriorityNodes">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentLowPriorityNodes { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentLowPriorityNodes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentLowPriorityNodes As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentLowPriorityNodes : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.CurrentLowPriorityNodes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentLowPriorityNodes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            数を取得します低優先度の計算ノード現在プールします。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeploymentConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration DeploymentConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property DeploymentConfiguration As DeploymentConfiguration" />
      <MemberSignature Language="F#" Value="member this.DeploymentConfiguration : Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DeploymentConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.deploymentConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.DeploymentConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            このプロパティは、プールのノードを展開する方法 - について説明を取得または設定のクラウド サービスまたは仮想マシンを使用します。
            </summary>
        <value>To be added.</value>
        <remarks>
            CloudServiceConfiguration を使用するには、VirtualMachineConfiguration で Azure Virtual Machines (IaaS) を使用して、Azure クラウド サービス (PaaS) を使用して、ノードを作成することを指定します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisplayName">
      <MemberSignature Language="C#" Value="public string DisplayName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DisplayName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberSignature Language="VB.NET" Value="Public Property DisplayName As String" />
      <MemberSignature Language="F#" Value="member this.DisplayName : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.DisplayName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.displayName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールの表示名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            表示名は一意でない必要があり、最大で 1,024 の最大長の Unicode 文字を含めることができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="InterNodeCommunication">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; InterNodeCommunication" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberSignature Language="VB.NET" Value="Public Property InterNodeCommunication As Nullable(Of InterNodeCommunicationState)" />
      <MemberSignature Language="F#" Value="member this.InterNodeCommunication : Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.InterNodeCommunication" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.interNodeCommunication")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.InterNodeCommunicationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールがノード間で直接通信を許可するかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、制限にノードをプールに割り当てることができます。 この値を有効にすると、プールに割り当てられるノードの要求された数の可能性を低減できます。 指定しない場合、この値が '無効' に既定値です。 使用可能な値が含まれます: 'Enabled'、'Disabled'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModified">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; LastModified { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; LastModified" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModified As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.LastModified : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.LastModified" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.lastModified")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プールの最終更新時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>
            これは、前回 targetDedicatedNodes や autoScaleSettings などのプール レベル データが変更されました。 コンピューティング ノードの状態を変更するなど、ノード レベルの変更には考慮されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxTasksPerNode">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; MaxTasksPerNode { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; MaxTasksPerNode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxTasksPerNode As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.MaxTasksPerNode : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.MaxTasksPerNode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.maxTasksPerNode")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の 1 つのコンピューティング ノードで同時に実行できるタスクの最大数を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてプールに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            バッチ サービスがメタデータに意味を割り当てませんこれは、ユーザー コードを使用するためだけです。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NetworkConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.NetworkConfiguration NetworkConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property NetworkConfiguration As NetworkConfiguration" />
      <MemberSignature Language="F#" Value="member this.NetworkConfiguration : Microsoft.Azure.Management.Batch.Models.NetworkConfiguration with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.NetworkConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.networkConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.NetworkConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプールのネットワーク構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt; ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As Nullable(Of PoolProvisioningState)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.Batch.Models.PoolProvisioningState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
             プールの現在の状態を取得します。
             </summary>
        <value>To be added.</value>
        <remarks>
             値は次のとおりです。
            
             成功 - プールは、コンピューティング ノードの可用性の対象のタスクを実行できるようにします。
             削除すると、ユーザーが、プールが削除されることを要求しましたが、削除操作がまだ完了していません。 使用可能な値が含まれます: は ' Succeeded'、'削除'
             </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            プールが、現在の状態を入力する時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResizeOperationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus ResizeOperationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResizeOperationStatus As ResizeOperationStatus" />
      <MemberSignature Language="F#" Value="member this.ResizeOperationStatus : Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ResizeOperationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.resizeOperationStatus")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ResizeOperationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得には、現在または最近完了したサイズ変更操作に関する詳細情報が含まれています。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.Batch.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定には、プール内のノードの数の構成を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartTask">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.StartTask StartTask { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.StartTask StartTask" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberSignature Language="VB.NET" Value="Public Property StartTask As StartTask" />
      <MemberSignature Language="F#" Value="member this.StartTask : Microsoft.Azure.Management.Batch.Models.StartTask with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.StartTask" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.startTask")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.StartTask</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または各コンピューティング ノードで、プールに参加を実行する指定されたタスクを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            修正プログラム (更新) 操作では、このプロパティは、プールから、開始タスクを削除する空のオブジェクトに設定できます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskSchedulingPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy TaskSchedulingPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskSchedulingPolicy As TaskSchedulingPolicy" />
      <MemberSignature Language="F#" Value="member this.TaskSchedulingPolicy : Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.TaskSchedulingPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.taskSchedulingPolicy")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Batch.Models.TaskSchedulingPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクのプール内のコンピューティング ノード間で配分する方法を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccounts">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.Batch.Models.UserAccount&gt; UserAccounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccounts As IList(Of UserAccount)" />
      <MemberSignature Language="F#" Value="member this.UserAccounts : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.UserAccounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.Batch.Models.UserAccount&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の各ノード上に作成されるユーザー アカウントの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.Pool.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="pool.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.Pool.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の仮想マシンのサイズを設定します。 プール内のすべての Vm は、同じサイズです。
            </summary>
        <value>To be added.</value>
        <remarks>
            クラウド サービス プール (プール cloudServiceConfiguration で作成された) の仮想マシンの利用可能なサイズについては、クラウド サービス (http://azure.microsoft.com/documentation/articles/cloud-services-sizes-specs/) のサイズを参照してください。
            バッチには、ExtraSmall を除くすべてのクラウド サービス VM サイズがサポートしています。 (プール virtualMachineConfiguration で作成した) 仮想マシンのマーケットプ レースからイメージを使用するプールの利用可能な VM サイズについては (Linux) (https://azure.microsoft.com/documentation/articles/ の仮想マシンのサイズを参照してください。仮想マシンの linux-サイズ/) または仮想マシン (Windows) (https://azure.microsoft.com/documentation/articles/virtual-machines-windows-sizes/) のサイズ。
            バッチには、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズがサポートしています。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>