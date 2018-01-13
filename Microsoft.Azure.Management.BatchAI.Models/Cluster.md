<Type Name="Cluster" FullName="Microsoft.Azure.Management.BatchAI.Models.Cluster">
  <TypeSignature Language="C#" Value="public class Cluster : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Cluster extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.Cluster" />
  <TypeSignature Language="VB.NET" Value="Public Class Cluster&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type Cluster = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            クラスターに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            クラスタ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Cluster (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string vmSize = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority = null, Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings = null, Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup = null, Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.ProvisioningState.Creating, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; allocationState = null, Nullable&lt;DateTime&gt; allocationStateTransitionTime = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors = null, Nullable&lt;int&gt; currentNodeCount = null, Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts nodeStateCounts = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string vmSize, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; vmPriority, class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings scaleSettings, class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration virtualMachineConfiguration, class Microsoft.Azure.Management.BatchAI.Models.NodeSetup nodeSetup, class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings userAccountSettings, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState provisioningState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; allocationState, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; allocationStateTransitionTime, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; errors, valuetype System.Nullable`1&lt;int32&gt; currentNodeCount, class Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts nodeStateCounts) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,System.Nullable{Microsoft.Azure.Management.BatchAI.Models.VmPriority},Microsoft.Azure.Management.BatchAI.Models.ScaleSettings,Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration,Microsoft.Azure.Management.BatchAI.Models.NodeSetup,Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings,Microsoft.Azure.Management.BatchAI.Models.ResourceId,System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.ProvisioningState,System.Nullable{System.DateTime},System.Nullable{Microsoft.Azure.Management.BatchAI.Models.AllocationState},System.Nullable{System.DateTime},System.Collections.Generic.IList{Microsoft.Azure.Management.BatchAI.Models.BatchAIError},System.Nullable{System.Int32},Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.Cluster : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; * Microsoft.Azure.Management.BatchAI.Models.ScaleSettings * Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration * Microsoft.Azure.Management.BatchAI.Models.NodeSetup * Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.ProvisioningState * Nullable&lt;DateTime&gt; * Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; * Nullable&lt;DateTime&gt; * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; * Nullable&lt;int&gt; * Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts -&gt; Microsoft.Azure.Management.BatchAI.Models.Cluster" Usage="new Microsoft.Azure.Management.BatchAI.Models.Cluster (id, name, type, location, tags, vmSize, vmPriority, scaleSettings, virtualMachineConfiguration, nodeSetup, userAccountSettings, subnet, creationTime, provisioningState, provisioningStateTransitionTime, allocationState, allocationStateTransitionTime, errors, currentNodeCount, nodeStateCounts)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="vmPriority" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;" />
        <Parameter Name="scaleSettings" Type="Microsoft.Azure.Management.BatchAI.Models.ScaleSettings" />
        <Parameter Name="virtualMachineConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration" />
        <Parameter Name="nodeSetup" Type="Microsoft.Azure.Management.BatchAI.Models.NodeSetup" />
        <Parameter Name="userAccountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="allocationState" Type="System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;" />
        <Parameter Name="allocationStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="errors" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;" />
        <Parameter Name="currentNodeCount" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="nodeStateCounts" Type="Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソースの名前</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所</param>
        <param name="tags">リソースのタグ</param>
        <param name="vmSize">クラスター内の仮想マシンのサイズ。</param>
        <param name="vmPriority">専用または lowpriority です。</param>
        <param name="scaleSettings">クラスターの必要な小数点以下桁数。</param>
        <param name="virtualMachineConfiguration">OS イメージと、マウントされたデータ ボリュームの設定です。</param>
        <param name="nodeSetup">クラスター内のすべてのコンピューティング ノードで実行するように設定します。</param>
        <param name="userAccountSettings">コンピューティング ノードのユーザー アカウントの設定です。</param>
        <param name="subnet">サブネットの識別子を指定します。</param>
        <param name="creationTime">クラスターの作成時間。</param>
        <param name="provisioningState">クラスターのプロビジョニングの状態を指定します。</param>
        <param name="provisioningStateTransitionTime">クラスターのプロビジョニング状態遷移の時間。</param>
        <param name="allocationState">クラスターのサイズを変更するかどうかを示します。</param>
        <param name="allocationStateTransitionTime">クラスターが現在の割り当て状態を入力する時刻。</param>
        <param name="errors">サイズ変更とノードのセットアップ タスクを含むクラスター上のさまざまなエラーの詳細が含まれます</param>
        <param name="currentNodeCount">クラスターに現在割り当てられている計算ノードの数。</param>
        <param name="nodeStateCounts">クラスター上のさまざまなノード状態の数。</param>
        <summary>
            クラスタ クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationState">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; AllocationState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt; AllocationState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationState As Nullable(Of AllocationState)" />
      <MemberSignature Language="F#" Value="member this.AllocationState : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.allocationState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.AllocationState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、クラスターのサイズを変更するかどうかを示します。
            </summary>
        <value>To be added.</value>
        <remarks>
            指定できる値は: 定常およびサイズ変更します。 安定した状態では、クラスターのサイズ変更がないことを示します。 進行状況では、クラスター内の計算ノードの数を変更することはありません。 クラスター状態が作成されるとき、およびコンピューティング ノードの数を変更するクラスターで操作が実行されているされないときに使用します。 状態のサイズを変更するには、クラスターがサイズ変更することを示しますつまり、コンピューティング ノードの中に追加またはクラスターから削除します。
            使用可能な値が含まれます: '定常'、'サイズを変更する'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AllocationStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; AllocationStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; AllocationStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AllocationStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.AllocationStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.AllocationStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            クラスターが現在の割り当て状態を入力するされた時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            クラスターの作成時刻を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentNodeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; CurrentNodeCount { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; CurrentNodeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.CurrentNodeCount" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CurrentNodeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.CurrentNodeCount : Nullable&lt;int&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.CurrentNodeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.currentNodeCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クラスターに現在割り当てられている計算ノードの数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Errors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; Errors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.Errors" />
      <MemberSignature Language="VB.NET" Value="Public Property Errors As IList(Of BatchAIError)" />
      <MemberSignature Language="F#" Value="member this.Errors : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.Errors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.errors")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.BatchAI.Models.BatchAIError&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定のサイズ変更およびノードのセットアップ タスクを含むクラスター上のさまざまなエラーの詳細が含まれています。
            </summary>
        <value>To be added.</value>
        <remarks>
            この要素には、ノードのセットアップ中にさまざまなコンピューティング ノードで発生したすべてのエラーが含まれています。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeSetup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeSetup NodeSetup" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeSetup" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeSetup As NodeSetup" />
      <MemberSignature Language="F#" Value="member this.NodeSetup : Microsoft.Azure.Management.BatchAI.Models.NodeSetup with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeSetup" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeSetup")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeSetup</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスター内のすべてのコンピューティング ノードで実行するセットアップを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeStateCounts">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts NodeStateCounts { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts NodeStateCounts" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeStateCounts" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeStateCounts As NodeStateCounts" />
      <MemberSignature Language="F#" Value="member this.NodeStateCounts : Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.NodeStateCounts" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.nodeStateCounts")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.NodeStateCounts</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            クラスター上のさまざまなノード状態の数を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.ProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As ProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.ProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、クラスターのプロビジョニングの状態を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値は、: - を作成するには、クラスターが作成されていることを指定します。 成功 - クラスターが正常に作成されたことを指定します。 失敗しました - クラスターの作成が失敗したことを指定します。 -を削除するには、クラスターが削除されていることを指定します。
            使用可能な値が含まれます: '作成中'、'成功'、''、' を削除できませんでした'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            クラスターのプロビジョニングの状態の移行時間を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScaleSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ScaleSettings ScaleSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.ScaleSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property ScaleSettings As ScaleSettings" />
      <MemberSignature Language="F#" Value="member this.ScaleSettings : Microsoft.Azure.Management.BatchAI.Models.ScaleSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.ScaleSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.scaleSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ScaleSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはクラスターの適切な規模を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サブネットの識別子を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UserAccountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings UserAccountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.UserAccountSettings" />
      <MemberSignature Language="VB.NET" Value="Public Property UserAccountSettings As UserAccountSettings" />
      <MemberSignature Language="F#" Value="member this.UserAccountSettings : Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.UserAccountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.userAccountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.UserAccountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードのユーザー アカウントの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.Cluster.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cluster.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="VirtualMachineConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration VirtualMachineConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VirtualMachineConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property VirtualMachineConfiguration As VirtualMachineConfiguration" />
      <MemberSignature Language="F#" Value="member this.VirtualMachineConfiguration : Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VirtualMachineConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.virtualMachineConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.VirtualMachineConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または OS イメージと、マウントされたデータ ボリュームの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VmPriority">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; VmPriority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VmPriority" />
      <MemberSignature Language="VB.NET" Value="Public Property VmPriority As Nullable(Of VmPriority)" />
      <MemberSignature Language="F#" Value="member this.VmPriority : Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt; with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VmPriority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmPriority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.BatchAI.Models.VmPriority&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定専用または lowpriority します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は専用です。 Lowpriority が選択された場合、タスクの実行中に、ノードを切断取得ことができます。 これは、ワークロードが再開できるチェックポイント処理である場合に最適です。 使用可能な値が含まれます: '専用'、'lowpriority'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.Cluster.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.Cluster.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
            取得またはクラスター内の仮想マシンのサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            クラスター内のすべての仮想マシンは、同じサイズです。 仮想マシンのマーケットプ レースからイメージを使用して、クラスターの使用可能な VM サイズについては ((Linux) の仮想マシンのサイズを参照してください (Windows) の仮想マシンのサイズ。 AI バッチ サービスは、STANDARD_A0 と premium storage (STANDARD_GS、STANDARD_DS、および STANDARD_DSV2 シリーズ) でそれらを除くすべての Azure VM サイズをサポートします。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>