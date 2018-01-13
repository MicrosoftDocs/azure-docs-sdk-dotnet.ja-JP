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
      <para>Service Fabric に報告されている名前と値のペアとしての名前、メトリックとランタイム値を表します。 負荷がクラスターを均等に使用して、ノードは、その容量を超えていないことを確認する Service Fabric で使用されるメトリックには、メトリックが与えられます。 <see cref="T:System.Fabric.LoadMetric" />使用して Service Fabric にレポートが用意されている<see cref="M:System.Fabric.IServicePartition.ReportLoad(System.Collections.Generic.IEnumerable{System.Fabric.LoadMetric})" />です。</para>
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
          <para>メトリックの名前。 この文字列がで指定されているメトリックの名前に一致する必要があります、<see cref="P:System.Fabric.Description.ServiceDescription.Metrics" />コレクション、またはこれらは無視されます。</para>
        </param>
        <param name="value">
          <para>整数としてのメトリックの現在の値。</para>
        </param>
        <summary>
          <para>作成して初期化、<see cref="T:System.Fabric.LoadMetric" />指定した名前と負荷の値を持つオブジェクト。</para>
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
          <para>サービスは、レポートを計画するメトリックの名前を示します。 </para>
        </summary>
        <value>
          <para><see cref="T:System.String" /> を返します。</para>
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
          <para>メトリックの現在の負荷を示します。</para>
        </summary>
        <value>
          <para><see cref="T:System.Int32" /> を返します。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>