<Type Name="LoadMetric" FullName="System.Fabric.LoadMetric">
  <TypeSignature Language="C#" Value="public sealed class LoadMetric" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit LoadMetric extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.LoadMetric" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class LoadMetric" />
  <TypeSignature Language="F#" Value="type LoadMetric = class" />
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
      <para><span data-ttu-id="f5612-101">Service Fabric に報告されている名前と値のペアとしての名前、メトリックとランタイム値を表します。</span><span class="sxs-lookup"><span data-stu-id="f5612-101">Represents the name of a metric and a runtime value as a name-value pair that is reported to Service Fabric.</span></span> <span data-ttu-id="f5612-102">負荷がクラスターを均等に使用して、ノードは、その容量を超えていないことを確認する Service Fabric で使用されるメトリックには、メトリックが与えられます。</span><span class="sxs-lookup"><span data-stu-id="f5612-102">The metric loads are used by Service Fabric to ensure that the cluster is evenly used and that nodes do not exceed their capacities for given metrics.</span></span> <span data-ttu-id="f5612-103"><see cref="T:System.Fabric.LoadMetric" />使用して Service Fabric にレポートが用意されている<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />です。</span><span class="sxs-lookup"><span data-stu-id="f5612-103"><see cref="T:System.Fabric.LoadMetric" /> reports are provided to Service Fabric via <see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />.</span></span></para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LoadMetric (string name, int value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, int32 value) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.LoadMetric.#ctor(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, value As Integer)" />
      <MemberSignature Language="F#" Value="new System.Fabric.LoadMetric : string * int -&gt; System.Fabric.LoadMetric" Usage="new System.Fabric.LoadMetric (name, value)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="value" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="name">
          <para><span data-ttu-id="f5612-104">メトリックの名前。</span><span class="sxs-lookup"><span data-stu-id="f5612-104">The name of the metric.</span></span> <span data-ttu-id="f5612-105">この文字列がで指定されているメトリックの名前に一致する必要があります、<see cref="P:System.Fabric.Description.ServiceDescription.Metrics" />コレクション、またはこれらは無視されます。</span><span class="sxs-lookup"><span data-stu-id="f5612-105">This string must match the names of the metrics that are specified in the <see cref="P:System.Fabric.Description.ServiceDescription.Metrics" /> collection, or they will be ignored.</span></span></para>
        </param>
        <param name="value">
          <para><span data-ttu-id="f5612-106">整数としてのメトリックの現在の値。</span><span class="sxs-lookup"><span data-stu-id="f5612-106">The current value of the metric as an integer.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="f5612-107">作成して初期化、<see cref="T:System.Fabric.LoadMetric" />指定した名前と負荷の値を持つオブジェクト。</span><span class="sxs-lookup"><span data-stu-id="f5612-107">Creates and initializes a <see cref="T:System.Fabric.LoadMetric" /> object with the specified name and load value.</span></span></para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LoadMetric.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="System.Fabric.LoadMetric.Name" />
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
          <para><span data-ttu-id="f5612-108">サービスは、レポートを計画するメトリックの名前を示します。</span><span class="sxs-lookup"><span data-stu-id="f5612-108">Indicates the name of the metric that the service plans to report.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="f5612-109"><see cref="T:System.String" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="f5612-109">Returns <see cref="T:System.String" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Value">
      <MemberSignature Language="C#" Value="public int Value { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Value" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.LoadMetric.Value" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Value As Integer" />
      <MemberSignature Language="F#" Value="member this.Value : int" Usage="System.Fabric.LoadMetric.Value" />
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
          <para><span data-ttu-id="f5612-110">メトリックの現在の負荷を示します。</span><span class="sxs-lookup"><span data-stu-id="f5612-110">Indicates the current load of the metric.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="f5612-111"><see cref="T:System.Int32" /> を返します。</span><span class="sxs-lookup"><span data-stu-id="f5612-111">Returns <see cref="T:System.Int32" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>