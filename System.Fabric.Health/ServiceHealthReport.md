<Type Name="ServiceHealthReport" FullName="System.Fabric.Health.ServiceHealthReport">
  <TypeSignature Language="C#" Value="public class ServiceHealthReport : System.Fabric.Health.HealthReport" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ServiceHealthReport extends System.Fabric.Health.HealthReport" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Health.ServiceHealthReport" />
  <TypeSignature Language="VB.NET" Value="Public Class ServiceHealthReport&#xA;Inherits HealthReport" />
  <TypeSignature Language="F#" Value="type ServiceHealthReport = class&#xA;    inherit HealthReport" />
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
      <para>サービス正常性エンティティに適用される正常性レポートを表します。
            使用して正常性ストアに、レポートが送信される<see cref="M:System.Fabric.FabricClient.HealthClient.ReportHealth(System.Fabric.Health.HealthReport)" />です。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ServiceHealthReport (Uri serviceName, System.Fabric.Health.HealthInformation healthInformation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri serviceName, class System.Fabric.Health.HealthInformation healthInformation) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Health.ServiceHealthReport.#ctor(System.Uri,System.Fabric.Health.HealthInformation)" />
      <MemberSignature Language="F#" Value="new System.Fabric.Health.ServiceHealthReport : Uri * System.Fabric.Health.HealthInformation -&gt; System.Fabric.Health.ServiceHealthReport" Usage="new System.Fabric.Health.ServiceHealthReport (serviceName, healthInformation)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="healthInformation" Type="System.Fabric.Health.HealthInformation" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>サービスの名前。 必須。</para>
        </param>
        <param name="healthInformation">
          <para>SourceId、プロパティ、ヘルス状態と同様に、レポート フィールドを記述する HealthInformation です。 必須。</para>
        </param>
        <summary>
          <para><see cref="T:System.Fabric.Health.ServiceHealthReport" /> の新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">
          <para>Null 値は、必須パラメーターに渡されました。</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceName">
      <MemberSignature Language="C#" Value="public Uri ServiceName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ServiceName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Health.ServiceHealthReport.ServiceName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceName As Uri" />
      <MemberSignature Language="F#" Value="member this.ServiceName : Uri" Usage="System.Fabric.Health.ServiceHealthReport.ServiceName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの名前を取得します。</para>
        </summary>
        <value>
          <para>サービスの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>