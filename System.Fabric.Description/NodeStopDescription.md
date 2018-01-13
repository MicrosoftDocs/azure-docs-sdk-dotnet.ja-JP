<Type Name="NodeStopDescription" FullName="System.Fabric.Description.NodeStopDescription">
  <TypeSignature Language="C#" Value="public sealed class NodeStopDescription : System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit NodeStopDescription extends System.Fabric.Description.NodeTransitionDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.NodeStopDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class NodeStopDescription&#xA;Inherits NodeTransitionDescription" />
  <TypeSignature Language="F#" Value="type NodeStopDescription = class&#xA;    inherit NodeTransitionDescription" />
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
            ノードがどのようにするかに関する情報を説明 StartNodeTransitionAsync() を使用して停止します。  
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeStopDescription (Guid operationId, string nodeName, System.Numerics.BigInteger nodeInstanceId, int stopDurationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Guid operationId, string nodeName, valuetype System.Numerics.BigInteger nodeInstanceId, int32 stopDurationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.#ctor(System.Guid,System.String,System.Numerics.BigInteger,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (operationId As Guid, nodeName As String, nodeInstanceId As BigInteger, stopDurationInSeconds As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Description.NodeStopDescription : Guid * string * System.Numerics.BigInteger * int -&gt; System.Fabric.Description.NodeStopDescription" Usage="new System.Fabric.Description.NodeStopDescription (operationId, nodeName, nodeInstanceId, stopDurationInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="operationId" Type="System.Guid" />
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="nodeInstanceId" Type="System.Numerics.BigInteger" />
        <Parameter Name="stopDurationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="operationId">この操作を識別する Guid です。  これは一意である必要があり、他の操作では使用できません。</param>
        <param name="nodeName">開始または停止するノードの名前です。  名前は、GetNodeListAsync() によって決定できます。</param>
        <param name="nodeInstanceId">ターゲット ノードのノード インスタンス id。  これは、GetNodeListAsync() によって決定できます。</param>
        <param name="stopDurationInSeconds">ノードを保持する期間が停止しました。  この時間を過ぎると、ノードが自動的に復帰します。  単位は秒単位です。  最小値は 600 で、最大値は 14400 です。</param>
        <summary>
            停止するノードに関する情報を記述するの NodeTransitionDescription を構築します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopDurationInSeconds">
      <MemberSignature Language="C#" Value="public int StopDurationInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 StopDurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StopDurationInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.StopDurationInSeconds : int" Usage="System.Fabric.Description.NodeStopDescription.StopDurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ノードを保持する期間が停止しました。  この時間を過ぎると、ノードが自動的に復帰します。  単位は秒単位です。  最小値は 600 で、最大値は 14400 です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.NodeStopDescription.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeStopDescription.ToString " />
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
            オブジェクトの文字列形式を出力します。
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>