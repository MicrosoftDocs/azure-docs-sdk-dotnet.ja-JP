<Type Name="DeployedServiceType" FullName="System.Fabric.Query.DeployedServiceType">
  <TypeSignature Language="C#" Value="public sealed class DeployedServiceType" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedServiceType extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedServiceType" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedServiceType" />
  <TypeSignature Language="F#" Value="type DeployedServiceType = class" />
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
      <para>展開済みサービスの種類を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedServiceType.CodePackageName" />
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
          <para>コード パッケージ名を取得します。</para>
        </summary>
        <value>
          <para>コード パッケージの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceManifestName" />
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
          <para>サービス マニフェスト名を取得します。</para>
        </summary>
        <value>
          <para>サービス マニフェストの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />
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
            サービス パッケージの ActivationId を取得します。
            </summary>
        <value>
          <para>
            展開済みサービス パッケージの ActivationId を表す文字列。 場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedServiceType.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeName">
      <MemberSignature Language="C#" Value="public string ServiceTypeName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceTypeName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeName : string" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeName" />
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
          <para>サービス型の名前を取得します。</para>
        </summary>
        <value>
          <para>サービスの種類の名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceTypeRegistrationStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.Query.ServiceTypeRegistrationStatus ServiceTypeRegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceTypeRegistrationStatus As ServiceTypeRegistrationStatus" />
      <MemberSignature Language="F#" Value="member this.ServiceTypeRegistrationStatus : System.Fabric.Query.ServiceTypeRegistrationStatus" Usage="System.Fabric.Query.DeployedServiceType.ServiceTypeRegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.ServiceTypeRegistrationStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>サービスの種類の登録状態を取得します。</para>
        </summary>
        <value>
          <para>サービス型の登録の状態です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>