<Type Name="UpgradeDomainProgress" FullName="System.Fabric.UpgradeDomainProgress">
  <TypeSignature Language="C#" Value="public sealed class UpgradeDomainProgress" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit UpgradeDomainProgress extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.UpgradeDomainProgress" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class UpgradeDomainProgress" />
  <TypeSignature Language="F#" Value="type UpgradeDomainProgress = class" />
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
      <para>アップグレード ドメイン内のノードのアップグレードの進行状況の詳細を表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="NodeProgressList">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt; NodeProgressList { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class System.Fabric.NodeUpgradeProgress&gt; NodeProgressList" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.UpgradeDomainProgress.NodeProgressList" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeProgressList As IList(Of NodeUpgradeProgress)" />
      <MemberSignature Language="F#" Value="member this.NodeProgressList : System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt;" Usage="System.Fabric.UpgradeDomainProgress.NodeProgressList" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.Fabric.NodeUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>一覧を取得<see cref="T:System.Fabric.NodeUpgradeProgress" />現在のアップグレード ドメイン内のノードのアップグレードの進行状況の詳細を示すです。</para>
        </summary>
        <value>
          <para>一連の<see cref="T:System.Fabric.NodeUpgradeProgress" />現在のアップグレード ドメイン内のノードのアップグレードの進行状況の詳細を示すです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeDomainName">
      <MemberSignature Language="C#" Value="public string UpgradeDomainName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string UpgradeDomainName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.UpgradeDomainProgress.UpgradeDomainName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeDomainName As String" />
      <MemberSignature Language="F#" Value="member this.UpgradeDomainName : string" Usage="System.Fabric.UpgradeDomainProgress.UpgradeDomainName" />
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
          <para>取得またはアップグレードを通過するアップグレード ドメインの名前を設定します。</para>
        </summary>
        <value>
          <para>アップグレードを通過するアップグレード ドメインの名前。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>