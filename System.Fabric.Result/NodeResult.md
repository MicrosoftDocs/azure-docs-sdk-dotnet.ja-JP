<Type Name="NodeResult" FullName="System.Fabric.Result.NodeResult">
  <TypeSignature Language="C#" Value="public class NodeResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit NodeResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Result.NodeResult" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeResult" />
  <TypeSignature Language="F#" Value="type NodeResult = class" />
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
            <span data-ttu-id="b410a-101">結果オブジェクトのノードを返します。</span><span class="sxs-lookup"><span data-stu-id="b410a-101">Returns Node result object.</span></span> 
            </summary>
    <remarks>
            <span data-ttu-id="b410a-102">このクラスは、nodeName と nodeInstanceId を返します。</span><span class="sxs-lookup"><span data-stu-id="b410a-102">This class returns nodeName and nodeInstanceId.</span></span> <span data-ttu-id="b410a-103">このクラスは、一部の RestartNode、StartNode、StopNode アクション結果構造体。</span><span class="sxs-lookup"><span data-stu-id="b410a-103">This class is part of RestartNode, StartNode, StopNode actions result structure.</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeInstance">
      <MemberSignature Language="C#" Value="public System.Numerics.BigInteger NodeInstance { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Numerics.BigInteger NodeInstance" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeInstance" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeInstance As BigInteger" />
      <MemberSignature Language="F#" Value="member this.NodeInstance : System.Numerics.BigInteger" Usage="System.Fabric.Result.NodeResult.NodeInstance" />
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
            <span data-ttu-id="b410a-104">ノード インスタンスの id を取得します。</span><span class="sxs-lookup"><span data-stu-id="b410a-104">Gets node instance id.</span></span>
            </summary>
        <value><span data-ttu-id="b410a-105">ノード インスタンスの id です。</span><span class="sxs-lookup"><span data-stu-id="b410a-105">The node instance id.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Result.NodeResult.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string" Usage="System.Fabric.Result.NodeResult.NodeName" />
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
            <span data-ttu-id="b410a-106">ノード名を取得します。</span><span class="sxs-lookup"><span data-stu-id="b410a-106">Gets node name.</span></span>
            </summary>
        <value><span data-ttu-id="b410a-107">ノード名。</span><span class="sxs-lookup"><span data-stu-id="b410a-107">The node name.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Result.NodeResult.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="nodeResult.ToString " />
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
            <span data-ttu-id="b410a-108">ように文字列を返します:"NodeName: 文字列、ノード インスタンス: BigInteger"</span><span class="sxs-lookup"><span data-stu-id="b410a-108">Returns a string like: "NodeName: string, NodeInstance: BigInteger"</span></span>
            </summary>
        <returns><span data-ttu-id="b410a-109">文字列</span><span class="sxs-lookup"><span data-stu-id="b410a-109">A string</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>