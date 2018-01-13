<Type Name="PackageSharingPolicy" FullName="System.Fabric.PackageSharingPolicy">
  <TypeSignature Language="C#" Value="public class PackageSharingPolicy" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PackageSharingPolicy extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.PackageSharingPolicy" />
  <TypeSignature Language="VB.NET" Value="Public Class PackageSharingPolicy" />
  <TypeSignature Language="F#" Value="type PackageSharingPolicy = class" />
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
      <para>パッケージを共有するためのポリシーを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PackageSharingPolicy (string packageName, System.Fabric.PackageSharingPolicyScope sharingScope);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string packageName, valuetype System.Fabric.PackageSharingPolicyScope sharingScope) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.PackageSharingPolicy.#ctor(System.String,System.Fabric.PackageSharingPolicyScope)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (packageName As String, sharingScope As PackageSharingPolicyScope)" />
      <MemberSignature Language="F#" Value="new System.Fabric.PackageSharingPolicy : string * System.Fabric.PackageSharingPolicyScope -&gt; System.Fabric.PackageSharingPolicy" Usage="new System.Fabric.PackageSharingPolicy (packageName, sharingScope)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="packageName" Type="System.String" />
        <Parameter Name="sharingScope" Type="System.Fabric.PackageSharingPolicyScope" />
      </Parameters>
      <Docs>
        <param name="packageName">
          <para>共有する必要がある特定のパッケージの名前です。 </para>
        </param>
        <param name="sharingScope">
          <para>コード、構成、データまたはすべてのパッケージを共有する必要があるかどうかを示すために PackageSharingPolicyScope パラメーター。 </para>
        </param>
        <summary>
          <para>
            PackageSharingPolicy オブジェクトを作成します。
            </para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PackageName">
      <MemberSignature Language="C#" Value="public string PackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageSharingPolicy.PackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PackageName As String" />
      <MemberSignature Language="F#" Value="member this.PackageName : string" Usage="System.Fabric.PackageSharingPolicy.PackageName" />
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
          <para>コード、構成、または共有すべきデータ パッケージの名前を取得します。</para>
        </summary>
        <value>
          <para>共有する必要があるコード、構成またはデータのパッケージの名前です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SharingScope">
      <MemberSignature Language="C#" Value="public System.Fabric.PackageSharingPolicyScope SharingScope { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.PackageSharingPolicyScope SharingScope" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.PackageSharingPolicy.SharingScope" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SharingScope As PackageSharingPolicyScope" />
      <MemberSignature Language="F#" Value="member this.SharingScope : System.Fabric.PackageSharingPolicyScope" Usage="System.Fabric.PackageSharingPolicy.SharingScope" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.PackageSharingPolicyScope</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>パッケージの共有ポリシーのスコープを取得します。</para>
        </summary>
        <value>
          <para>パッケージの共有ポリシーのスコープです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>