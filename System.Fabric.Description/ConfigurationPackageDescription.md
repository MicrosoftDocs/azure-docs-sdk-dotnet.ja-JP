<Type Name="ConfigurationPackageDescription" FullName="System.Fabric.Description.ConfigurationPackageDescription">
  <TypeSignature Language="C#" Value="public sealed class ConfigurationPackageDescription : System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ConfigurationPackageDescription extends System.Fabric.Description.PackageDescription" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ConfigurationPackageDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ConfigurationPackageDescription&#xA;Inherits PackageDescription" />
  <TypeSignature Language="F#" Value="type ConfigurationPackageDescription = class&#xA;    inherit PackageDescription" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.Description.PackageDescription</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para>構成パッケージをについて説明します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Settings">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.ConfigurationSettings Settings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.ConfigurationSettings Settings" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ConfigurationPackageDescription.Settings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Settings As ConfigurationSettings" />
      <MemberSignature Language="F#" Value="member this.Settings : System.Fabric.Description.ConfigurationSettings" Usage="System.Fabric.Description.ConfigurationPackageDescription.Settings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use Settings property of System.Fabric.ConfigurationPackage type.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.ConfigurationSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>推奨されなくなりました。 構成パッケージから解析された構成設定を取得します。</para>
        </summary>
        <value>
          <para>構成パッケージから解析された構成設定。</para>
        </value>
        <remarks>このプロパティは今後使用しません。 代わりに System.Fabric.ConfigurationPackage 型のプロパティを設定します。</remarks>
      </Docs>
    </Member>
  </Members>
</Type>