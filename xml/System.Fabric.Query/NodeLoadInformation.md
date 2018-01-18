<Type Name="NodeLoadInformation" FullName="System.Fabric.Query.NodeLoadInformation">
  <TypeSignature Language="C#" Value="public class NodeLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.NodeLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeLoadInformation" />
  <TypeSignature Language="F#" Value="type NodeLoadInformation = class" />
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
      <para><span data-ttu-id="0b7c6-101">特定のノードのすべてのメトリックとその負荷の概要を保持しているデータ構造を表します。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-101">Represents the data structure that holds a summary of all metrics and their load on a certain node.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.NodeLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="0b7c6-102"><see cref="T:System.Fabric.Query.NodeLoadInformation" /> クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-102">Initializes a new instance of the <see cref="T:System.Fabric.Query.NodeLoadInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeLoadMetricInformationList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.NodeLoadMetricInformation&gt; NodeLoadMetricInformationList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.NodeLoadMetricInformation&gt; NodeLoadMetricInformationList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadInformation.NodeLoadMetricInformationList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeLoadMetricInformationList As IList(Of NodeLoadMetricInformation)" />
      <MemberSignature Language="F#" Value="member this.NodeLoadMetricInformationList : System.Collections.Generic.IList&lt;System.Fabric.Query.NodeLoadMetricInformation&gt;" Usage="System.Fabric.Query.NodeLoadInformation.NodeLoadMetricInformationList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.NodeLoadMetricInformation&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="0b7c6-103">メトリックとノードで、読み込み情報を含む一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-103">Gets the list that contains metrics and their load information on a node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0b7c6-104">この一覧は、メトリックとノードの場合は、そのロード情報が含まれています。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-104">The list that contains metrics and their load information on a node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeName">
      <MemberSignature Language="C#" Value="public string NodeName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.NodeLoadInformation.NodeName" />
      <MemberSignature Language="VB.NET" Value="Public Property NodeName As String" />
      <MemberSignature Language="F#" Value="member this.NodeName : string with get, set" Usage="System.Fabric.Query.NodeLoadInformation.NodeName" />
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
          <para><span data-ttu-id="0b7c6-105">ノードの名前を取得します。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-105">Gets the name of the node.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="0b7c6-106">ノード名。</span><span class="sxs-lookup"><span data-stu-id="0b7c6-106">The name of the node.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>