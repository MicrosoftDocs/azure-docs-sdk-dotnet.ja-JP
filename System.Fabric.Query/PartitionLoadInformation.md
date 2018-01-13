<Type Name="PartitionLoadInformation" FullName="System.Fabric.Query.PartitionLoadInformation">
  <TypeSignature Language="C#" Value="public class PartitionLoadInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PartitionLoadInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.PartitionLoadInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PartitionLoadInformation" />
  <TypeSignature Language="F#" Value="type PartitionLoadInformation = class" />
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
      <para><span data-ttu-id="f6fa1-101">パーティションの読み込み情報を表します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-101">Represents the partition load information.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PartitionLoadInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.PartitionLoadInformation.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><span data-ttu-id="f6fa1-102"><see cref="T:System.Fabric.Query.PartitionLoadInformation" /> クラスのインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-102">Initializes an instance of the <see cref="T:System.Fabric.Query.PartitionLoadInformation" /> class.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionId">
      <MemberSignature Language="C#" Value="public Guid PartitionId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid PartitionId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.PartitionId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PartitionId As Guid" />
      <MemberSignature Language="F#" Value="member this.PartitionId : Guid" Usage="System.Fabric.Query.PartitionLoadInformation.PartitionId" />
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
          <para><span data-ttu-id="f6fa1-103">パーティション ID を取得します</span><span class="sxs-lookup"><span data-stu-id="f6fa1-103">Gets the partition ID.</span></span> <span data-ttu-id="f6fa1-104">このコマンドは、パイプ処理の目的として使用できます。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-104">This command can be used as piping purpose.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f6fa1-105">パーティションの id。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-105">The partition ID.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryLoadMetricReports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; PrimaryLoadMetricReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; PrimaryLoadMetricReports" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.PrimaryLoadMetricReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryLoadMetricReports As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.PrimaryLoadMetricReports : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.PartitionLoadInformation.PrimaryLoadMetricReports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f6fa1-106">このパーティションの主な役割の負荷のレポートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-106">Gets the list of load reports for primary role of this partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f6fa1-107">負荷の一覧は、このパーティションの主な役割を報告します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-107">The list of load reports for primary role of this partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryLoadMetricReports">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt; SecondaryLoadMetricReports { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.Query.LoadMetricReport&gt; SecondaryLoadMetricReports" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.PartitionLoadInformation.SecondaryLoadMetricReports" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SecondaryLoadMetricReports As IList(Of LoadMetricReport)" />
      <MemberSignature Language="F#" Value="member this.SecondaryLoadMetricReports : System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;" Usage="System.Fabric.Query.PartitionLoadInformation.SecondaryLoadMetricReports" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.Query.LoadMetricReport&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="f6fa1-108">このパーティションのセカンダリ ロールのロード レポートの一覧を取得します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-108">Gets the list of load reports for secondary role of this partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f6fa1-109">このパーティションのセカンダリ ロールのロードの一覧を報告します。</span><span class="sxs-lookup"><span data-stu-id="f6fa1-109">The list of load reports for secondary role of this partition.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>