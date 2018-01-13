<Type Name="DeployedCodePackage" FullName="System.Fabric.Query.DeployedCodePackage">
  <TypeSignature Language="C#" Value="public sealed class DeployedCodePackage" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit DeployedCodePackage extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.DeployedCodePackage" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class DeployedCodePackage" />
  <TypeSignature Language="F#" Value="type DeployedCodePackage = class" />
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
      <para>配置されたコード パッケージを表します。</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CodePackageName">
      <MemberSignature Language="C#" Value="public string CodePackageName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.CodePackageName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageName As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageName : string" Usage="System.Fabric.Query.DeployedCodePackage.CodePackageName" />
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
    <Member MemberName="CodePackageVersion">
      <MemberSignature Language="C#" Value="public string CodePackageVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CodePackageVersion" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.CodePackageVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CodePackageVersion As String" />
      <MemberSignature Language="F#" Value="member this.CodePackageVersion : string" Usage="System.Fabric.Query.DeployedCodePackage.CodePackageVersion" />
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
          <para>コード パッケージのバージョンを取得します。</para>
        </summary>
        <value>
          <para>コード パッケージのバージョン。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeployedCodePackageStatus">
      <MemberSignature Language="C#" Value="public System.Fabric.DeploymentStatus DeployedCodePackageStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.DeploymentStatus DeployedCodePackageStatus" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.DeployedCodePackageStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DeployedCodePackageStatus As DeploymentStatus" />
      <MemberSignature Language="F#" Value="member this.DeployedCodePackageStatus : System.Fabric.DeploymentStatus" Usage="System.Fabric.Query.DeployedCodePackage.DeployedCodePackageStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.DeploymentStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>コード パッケージの状態を取得します。</para>
        </summary>
        <value>
          <para>配置されたコード パッケージのステータス。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.CodePackageEntryPoint EntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.CodePackageEntryPoint EntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.EntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EntryPoint As CodePackageEntryPoint" />
      <MemberSignature Language="F#" Value="member this.EntryPoint : System.Fabric.Query.CodePackageEntryPoint" Usage="System.Fabric.Query.DeployedCodePackage.EntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.CodePackageEntryPoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>メイン エントリ ポイントを取得します。</para>
        </summary>
        <value>
          <para>メイン エントリ ポイント。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostIsolationMode">
      <MemberSignature Language="C#" Value="public System.Fabric.HostIsolationMode HostIsolationMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.HostIsolationMode HostIsolationMode" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.HostIsolationMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostIsolationMode As HostIsolationMode" />
      <MemberSignature Language="F#" Value="member this.HostIsolationMode : System.Fabric.HostIsolationMode" Usage="System.Fabric.Query.DeployedCodePackage.HostIsolationMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostIsolationMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.HostIsolationMode" />のメイン エントリ ポイントです。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.HostIsolationMode" />のメイン エントリ ポイントです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostType">
      <MemberSignature Language="C#" Value="public System.Fabric.HostType HostType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.HostType HostType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.HostType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostType As HostType" />
      <MemberSignature Language="F#" Value="member this.HostType : System.Fabric.HostType" Usage="System.Fabric.Query.DeployedCodePackage.HostType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.HostType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>取得、<see cref="T:System.Fabric.HostType" />のメイン エントリ ポイントです。</para>
        </summary>
        <value>
          <para><see cref="T:System.Fabric.HostType" />のメイン エントリ ポイントです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunFrequencyInterval">
      <MemberSignature Language="C#" Value="public long RunFrequencyInterval { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 RunFrequencyInterval" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.RunFrequencyInterval" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RunFrequencyInterval As Long" />
      <MemberSignature Language="F#" Value="member this.RunFrequencyInterval : int64" Usage="System.Fabric.Query.DeployedCodePackage.RunFrequencyInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>実行頻度の間隔を取得します。</para>
        </summary>
        <value>
          <para>実行頻度の間隔。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceManifestName">
      <MemberSignature Language="C#" Value="public string ServiceManifestName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServiceManifestName" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.ServiceManifestName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceManifestName As String" />
      <MemberSignature Language="F#" Value="member this.ServiceManifestName : string" Usage="System.Fabric.Query.DeployedCodePackage.ServiceManifestName" />
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
          <para>サービス マニフェスト名です。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServicePackageActivationId">
      <MemberSignature Language="C#" Value="public string ServicePackageActivationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ServicePackageActivationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServicePackageActivationId As String" />
      <MemberSignature Language="F#" Value="member this.ServicePackageActivationId : string" Usage="System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />
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
            表す文字列<see cref="P:System.Fabric.Query.DeployedServicePackage.ServicePackageActivationId" />展開済みサービス パッケージのです。 場合<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />サービスの作成時に指定した<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />(が指定されていない場合に既定値はまたは<see cref="F:System.Fabric.Description.ServicePackageActivationMode.SharedProcess" />)、次の値が<see cref="P:System.Fabric.Query.DeployedCodePackage.ServicePackageActivationId" />は常に空の文字列。
            詳細をご覧ください。<see cref="T:System.Fabric.Description.ServicePackageActivationMode" />です。
            </para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetupEntryPoint">
      <MemberSignature Language="C#" Value="public System.Fabric.Query.CodePackageEntryPoint SetupEntryPoint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.Query.CodePackageEntryPoint SetupEntryPoint" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.DeployedCodePackage.SetupEntryPoint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SetupEntryPoint As CodePackageEntryPoint" />
      <MemberSignature Language="F#" Value="member this.SetupEntryPoint : System.Fabric.Query.CodePackageEntryPoint" Usage="System.Fabric.Query.DeployedCodePackage.SetupEntryPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.Query.CodePackageEntryPoint</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>セットアップ エントリ ポイントを取得します。</para>
        </summary>
        <value>
          <para>セットアップ エントリ ポイントです。</para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>