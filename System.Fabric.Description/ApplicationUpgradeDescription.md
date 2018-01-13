<Type Name="ApplicationUpgradeDescription" FullName="System.Fabric.Description.ApplicationUpgradeDescription">
  <TypeSignature Language="C#" Value="public sealed class ApplicationUpgradeDescription" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ApplicationUpgradeDescription extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Description.ApplicationUpgradeDescription" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ApplicationUpgradeDescription" />
  <TypeSignature Language="F#" Value="type ApplicationUpgradeDescription = class" />
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
      <para>
            アップグレードのポリシーとアプリケーションをアップグレードするについて説明します。
            </para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ApplicationUpgradeDescription ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Description.ApplicationUpgradeDescription.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
          <para><see cref="T:System.Fabric.Description.ApplicationUpgradeDescription" /> クラスの新しいインスタンスを初期化します。</para>
        </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationName">
      <MemberSignature Language="C#" Value="public Uri ApplicationName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri ApplicationName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.ApplicationName" />
      <MemberSignature Language="VB.NET" Value="Public Property ApplicationName As Uri" />
      <MemberSignature Language="F#" Value="member this.ApplicationName : Uri with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.ApplicationName" />
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
          <para>取得またはにアップグレードする必要があるアプリケーション インスタンスの URI 名を設定します。</para>
        </summary>
        <value>
          <para>アップグレードする必要があるアプリケーション インスタンスの URI 名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplicationParameters">
      <MemberSignature Language="C#" Value="public System.Collections.Specialized.NameValueCollection ApplicationParameters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Specialized.NameValueCollection ApplicationParameters" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.ApplicationParameters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationParameters As NameValueCollection" />
      <MemberSignature Language="F#" Value="member this.ApplicationParameters : System.Collections.Specialized.NameValueCollection" Usage="System.Fabric.Description.ApplicationUpgradeDescription.ApplicationParameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Specialized.NameValueCollection</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得または設定、ApplicationManifest.xml で指定されているパラメーターの名前と値ペアのコレクション。</para>
        </summary>
        <value>
          <para>ApplicationManifest.xml で指定されているパラメーターの名前と値のペアのコレクション。</para>
        </value>
        <remarks>
            パラメーターの値の許容最大長は、1024 * 1024 文字 (終端の null 文字を含む) です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetApplicationTypeVersion">
      <MemberSignature Language="C#" Value="public string TargetApplicationTypeVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetApplicationTypeVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.TargetApplicationTypeVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetApplicationTypeVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetApplicationTypeVersion : string with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.TargetApplicationTypeVersion" />
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
          <para>取得またはアプリケーション インスタンスのアップグレード先アプリケーションの種類のバージョンを設定します。</para>
        </summary>
        <value>
          <para>アプリケーション インスタンスのアップグレード先アプリケーションの種類のバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradePolicyDescription">
      <MemberSignature Language="C#" Value="public System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Description.UpgradePolicyDescription UpgradePolicyDescription" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Description.ApplicationUpgradeDescription.UpgradePolicyDescription" />
      <MemberSignature Language="VB.NET" Value="Public Property UpgradePolicyDescription As UpgradePolicyDescription" />
      <MemberSignature Language="F#" Value="member this.UpgradePolicyDescription : System.Fabric.Description.UpgradePolicyDescription with get, set" Usage="System.Fabric.Description.ApplicationUpgradeDescription.UpgradePolicyDescription" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Description.UpgradePolicyDescription</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得またはこのアプリケーションのインスタンスをアップグレードするために使用するポリシーの説明を設定します。</para>
        </summary>
        <value>
          <para>このアプリケーションのインスタンスをアップグレードするために使用するポリシーの説明です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>