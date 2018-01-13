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
      <para>特定のノードのすべてのメトリックとその負荷の概要を保持しているデータ構造を表します。</para>
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
          <para><see cref="T:System.Fabric.Query.NodeLoadInformation" /> クラスの新しいインスタンスを初期化します。</para>
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
          <para>メトリックとノードで、読み込み情報を含む一覧を取得します。</para>
        </summary>
        <value>
          <para>この一覧は、メトリックとノードの場合は、そのロード情報が含まれています。</para>
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
          <para>ノードの名前を取得します。</para>
        </summary>
        <value>
          <para>ノード名。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>