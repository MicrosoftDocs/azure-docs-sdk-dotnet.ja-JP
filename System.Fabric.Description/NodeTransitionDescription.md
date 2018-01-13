<Type Name="NodeTransitionDescription" FullName="System.Fabric.Description.NodeTransitionDescription">
  <TypeSignature Language="C#" Value="public abstract class NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit NodeTransitionDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeTransitionDescription = class" />
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
            ノードが、移行する必要があり、StartNodeTransitionAsync() と共に使用される方法に関する情報について説明します。  
            このオブジェクトを直接使用できませんが、派生クラスを使用する必要があります。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected NodeTransitionDescription (System.Fabric.NodeTransitionType nodeTransitionType, Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(valuetype System.Fabric.NodeTransitionType nodeTransitionType, valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeTransitionDescription.#ctor(System.Fabric.NodeTransitionType,System.Guid,System.String,System.Numerics.BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeTransitionDescription : System.Fabric.NodeTransitionType * Guid * string * System.Numerics.BigInteger -&gt; System.Fabric.Description.NodeTransitionDescription" Usage="new System.Fabric.Description.NodeTransitionDescription (nodeTransitionType, operationId, nodeName, nodeInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="nodeTransitionType" Type="System.Fabric.NodeTransitionType" />
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="nodeTransitionType">実行する移行の種類を示します。  NodeTransitionType.Start 停止したノードが開始されます。  NodeTransitionType.Stop では、上にあるノードを停止します。</param>
        <param name="operationId">この操作を識別する Guid です。  これは一意である必要があり、他の操作では使用できません。</param>
        <param name="nodeName">開始または停止するノードの名前です。  名前は、GetNodeListAsync() によって決定できます。</param>
        <param name="nodeInstanceId">ターゲット ノードのノード インスタンス id。  これは、GetNodeListAsync() によって決定できます。</param>
        <summary>
            コンス トラクター、NodeTransitionDescription
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeInstanceId">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstanceId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstanceId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeTransitionDescription.NodeInstanceId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstanceId As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstanceId : System.Numerics.BigInteger" Usage="System.Fabric.Description.NodeTransitionDescription.NodeInstanceId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Numerics.BigInteger</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ターゲット ノードのノード インスタンス id。  これは、GetNodeListAsync() によって決定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeTransitionDescription.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Description.NodeTransitionDescription.NodeName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            開始または停止するノードの名前です。  名前は、GetNodeListAsync() によって決定できます。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeTransitionType">
      <MemberSignature Language="C#" Value="public System.Fabric.NodeTransitionType NodeTransitionType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.NodeTransitionType NodeTransitionType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeTransitionDescription.NodeTransitionType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeTransitionType As NodeTransitionType" />
      <MemberSignature Language="F#" Value="member this.NodeTransitionType : System.Fabric.NodeTransitionType" Usage="System.Fabric.Description.NodeTransitionDescription.NodeTransitionType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.NodeTransitionType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            NodeTransitionType を実行する移行の種類を決定します。  開始、停止したノードが開始されます。  停止では、最新のノードを停止します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeTransitionDescription.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="System.Fabric.Description.NodeTransitionDescription.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            この操作を識別する Guid です。  これは一意である必要があり、他の操作では使用できません。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeTransitionDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeTransitionDescription.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このオブジェクトの文字列形式を出力します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>