<Type Name="JobPatchParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter">
  <TypeSignature Language="C#" Value="public class JobPatchParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit JobPatchParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class JobPatchParameter" />
  <TypeSignature Language="F#" Value="type JobPatchParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ジョブに対する変更のセット。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            JobPatchParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public JobPatchParameter (Nullable&lt;int&gt; priority = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete = null, Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints = null, Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; priority, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; onAllTasksComplete, class Microsoft.Azure.Batch.Protocol.Models.JobConstraints constraints, class Microsoft.Azure.Batch.Protocol.Models.PoolInformation poolInfo, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; metadata) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.#ctor(System.Nullable{System.Int32},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete},Microsoft.Azure.Batch.Protocol.Models.JobConstraints,Microsoft.Azure.Batch.Protocol.Models.PoolInformation,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.MetadataItem})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional priority As Nullable(Of Integer) = null, Optional onAllTasksComplete As Nullable(Of OnAllTasksComplete) = null, Optional constraints As JobConstraints = null, Optional poolInfo As PoolInformation = null, Optional metadata As IList(Of MetadataItem) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter : Nullable&lt;int&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; * Microsoft.Azure.Batch.Protocol.Models.JobConstraints * Microsoft.Azure.Batch.Protocol.Models.PoolInformation * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter (priority, onAllTasksComplete, constraints, poolInfo, metadata)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="priority" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="onAllTasksComplete" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;" />
        <Parameter Name="constraints" Type="Microsoft.Azure.Batch.Protocol.Models.JobConstraints" />
        <Parameter Name="poolInfo" Type="Microsoft.Azure.Batch.Protocol.Models.PoolInformation" />
        <Parameter Name="metadata" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;" />
      </Parameters>
      <Docs>
        <param name="priority">ジョブの優先度です。</param>
        <param name="onAllTasksComplete">アクション、バッチ サービスは必要があります、ジョブ内のすべてのタスクが完了した状態となります。</param>
        <param name="constraints">ジョブの実行制約。</param>
        <param name="poolInfo">バッチ サービスがジョブのタスクを実行するプールです。</param>
        <param name="metadata">ジョブにメタデータとして関連付けられた名前と値のペアの一覧。</param>
        <summary>
            JobPatchParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Constraints">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.JobConstraints Constraints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
      <MemberSignature Language="VB.NET" Value="Public Property Constraints As JobConstraints" />
      <MemberSignature Language="F#" Value="member this.Constraints : Microsoft.Azure.Batch.Protocol.Models.JobConstraints with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Constraints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="constraints")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobConstraints</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの実行の制約を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、制約のままにする既存の実行は変更されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Metadata">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; Metadata" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
      <MemberSignature Language="VB.NET" Value="Public Property Metadata As IList(Of MetadataItem)" />
      <MemberSignature Language="F#" Value="member this.Metadata : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Metadata" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="metadata")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.MetadataItem&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはメタデータとしてジョブに関連付けられている名前と値のペアの一覧を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既存のジョブ メタデータが左で省略すると、変更されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OnAllTasksComplete">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; OnAllTasksComplete" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberSignature Language="VB.NET" Value="Public Property OnAllTasksComplete As Nullable(Of OnAllTasksComplete)" />
      <MemberSignature Language="F#" Value="member this.OnAllTasksComplete : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.OnAllTasksComplete" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="onAllTasksComplete")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OnAllTasksComplete&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ ジョブ内のすべてのタスクが完了の状態でサービスが行うアクションを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            補完の動作が左を省略すると、変更されません。 NoAction に terminateJob から値を変更することがありますされません - は、ジョブの自動終了が関与して、一度を有効にできません再度オフします。 これを実行しようとすると、要求は '無効なプロパティ値' エラー応答; が失敗します。REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。 使用可能な値が含まれます: 'noAction'、'terminateJob'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.PoolInformation PoolInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolInfo As PoolInformation" />
      <MemberSignature Language="F#" Value="member this.PoolInfo : Microsoft.Azure.Batch.Protocol.Models.PoolInformation with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.PoolInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolInfo")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.PoolInformation</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはバッチ サービスがジョブのタスクを実行するプールを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            ジョブが無効になっている場合にのみ、ジョブのプールを変更することがあります。
            PoolInfo 要素を含めるし、ジョブが無効になっていない更新プログラムのジョブの呼び出しは失敗します。 KeepAlive プロパティのみを更新できる場合は、poolInfo で autoPoolSpecification 仕様を指定すると、し、自動プールのジョブの poolLifetimeOption がある場合のみです。 省略した場合、ジョブは引き続き、現在のプールで実行されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Priority { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberSignature Language="VB.NET" Value="Public Property Priority As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Priority : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="priority")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはジョブの優先順位を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            優先順位の値の範囲は -1000 から 1000、-1000 が最も低い優先度と 1000 中優先順位が高いです。 ジョブの優先度が左で省略すると、変更されません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.JobPatchParameter.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="jobPatchParameter.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
  </Members>
</Type>