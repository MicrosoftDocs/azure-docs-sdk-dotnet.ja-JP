<Type Name="NodeStartDescription" FullName="System.Fabric.Description.NodeStartDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeStartDescription : System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeStartDescription extends System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeStartDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeStartDescription&#xA;Inherits NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeStartDescription = class&#xA;    inherit NodeTransitionDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.NodeTransitionDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            ノードがどのようにするかに関する情報を説明 StartNodeTransitionAsync() の使用を開始します。  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStartDescription (Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStartDescription.#ctor(System.Guid,System.String,System.Numerics.BigInteger)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationId As Guid, nodeName As String, nodeInstanceId As BigInteger)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeStartDescription : Guid * string * System.Numerics.BigInteger -&gt; System.Fabric.Description.NodeStartDescription" Usage="new System.Fabric.Description.NodeStartDescription (operationId, nodeName, nodeInstanceId)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
      </Parameters>
      <Docs>
        <param name="operationId">この操作を識別する Guid です。  これは一意である必要があり、他の操作では使用できません。</param>
        <param name="nodeName">開始または停止するノードの名前です。  名前は、GetNodeListAsync() によって決定できます。</param>
        <param name="nodeInstanceId">ターゲット ノードのノード インスタンス id。  これは、GetNodeListAsync() によって決定できます。</param>
        <summary>
            ノードがどのようにするかに関する情報を説明する NodeStartDescription のインスタンスを作成する StartNodeTransitionAsync() の使用を開始します。  
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>