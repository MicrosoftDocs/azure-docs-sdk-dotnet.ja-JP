<Type Name="ComputeNodeInformation" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation">
  <TypeSignature Language="C#" Value="public class ComputeNodeInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeInformation" />
  <TypeSignature Language="F#" Value="type ComputeNodeInformation = class" />
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
            タスクが実行したコンピューティング ノードに関する情報です。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.#ctor" />
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
            ComputeNodeInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeInformation (string affinityId = null, string nodeUrl = null, string poolId = null, string nodeId = null, string taskRootDirectory = null, string taskRootDirectoryUrl = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string affinityId, string nodeUrl, string poolId, string nodeId, string taskRootDirectory, string taskRootDirectoryUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.#ctor(System.String,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional affinityId As String = null, Optional nodeUrl As String = null, Optional poolId As String = null, Optional nodeId As String = null, Optional taskRootDirectory As String = null, Optional taskRootDirectoryUrl As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation : string * string * string * string * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation (affinityId, nodeUrl, poolId, nodeId, taskRootDirectory, taskRootDirectoryUrl)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="affinityId" Type="System.String" />
        <Parameter Name="nodeUrl" Type="System.String" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="taskRootDirectory" Type="System.String" />
        <Parameter Name="taskRootDirectoryUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="affinityId">渡すことができるスケジュール タスクを要求できるタスクを追加するときにこのコンピューティング ノードでタスクが実行したコンピューティング ノードの識別子。</param>
        <param name="nodeUrl">タスクが実行されたノードの URL です。
            </param>
        <param name="poolId">タスクが実行されたプールの ID。</param>
        <param name="nodeId">タスクが実行されたノードの ID。</param>
        <param name="taskRootDirectory">コンピューティング ノード上のタスクのルート ディレクトリ。</param>
        <param name="taskRootDirectoryUrl">コンピューティング ノード上のタスクのルート ディレクトリの URL です。</param>
        <summary>
            ComputeNodeInformation クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AffinityId">
      <MemberSignature Language="C#" Value="public string AffinityId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AffinityId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.AffinityId" />
      <MemberSignature Language="VB.NET" Value="Public Property AffinityId As String" />
      <MemberSignature Language="F#" Value="member this.AffinityId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.AffinityId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="affinityId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはこのコンピューティング ノードでタスクをスケジュールすることを要求するタスクを追加するときに渡すことができるタスクが実行したコンピューティング ノードの識別子を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeId">
      <MemberSignature Language="C#" Value="public string NodeId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.NodeId" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeId As String" />
      <MemberSignature Language="F#" Value="member this.NodeId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.NodeId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが実行されたノードの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeUrl">
      <MemberSignature Language="C#" Value="public string NodeUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.NodeUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeUrl As String" />
      <MemberSignature Language="F#" Value="member this.NodeUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.NodeUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="nodeUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが実行されたノードの URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.PoolId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="poolId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはタスクが実行されたプールの ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectory">
      <MemberSignature Language="C#" Value="public string TaskRootDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.TaskRootDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectory As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectory : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.TaskRootDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードで、タスクのルート ディレクトリを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TaskRootDirectoryUrl">
      <MemberSignature Language="C#" Value="public string TaskRootDirectoryUrl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TaskRootDirectoryUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.TaskRootDirectoryUrl" />
      <MemberSignature Language="VB.NET" Value="Public Property TaskRootDirectoryUrl As String" />
      <MemberSignature Language="F#" Value="member this.TaskRootDirectoryUrl : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeInformation.TaskRootDirectoryUrl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="taskRootDirectoryUrl")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードでタスクのルート ディレクトリに URL を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>