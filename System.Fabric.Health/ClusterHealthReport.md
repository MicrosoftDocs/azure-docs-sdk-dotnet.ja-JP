<Type Name="ClusterHealthReport" FullName="System.Fabric.Health.ClusterHealthReport">
  <TypeSignature Language="C#" Value="public class ClusterHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ClusterHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ClusterHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class ClusterHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type ClusterHealthReport = class&#xA;    inherit HealthReport" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Health.HealthReport</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>クラスターの正常性エンティティに適用される正常性レポートを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ClusterHealthReport (System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ClusterHealthReport.#ctor(System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ClusterHealthReport : System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.ClusterHealthReport" Usage="new System.Fabric.Health.ClusterHealthReport healthInformation" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="healthInformation">
          <para>レポートのパラメーターを記述するヘルス情報です。 null にすることはできません。</para>
        </param>
        <summary>
          <para>クラスターの正常性レポートを作成します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Null 値は、必須パラメーターに渡されました。</para>
        </exception>
      </Docs>
    </Member>
  </Members>
</Type>