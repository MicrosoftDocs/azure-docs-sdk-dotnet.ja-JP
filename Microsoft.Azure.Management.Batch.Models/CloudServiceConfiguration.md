<Type Name="CloudServiceConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration">
  <TypeSignature Language="C#" Value="public class CloudServiceConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudServiceConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudServiceConfiguration" />
  <TypeSignature Language="F#" Value="type CloudServiceConfiguration = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Azure クラウド サービス プラットフォームに基づいて、プール内のノードで構成します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            CloudServiceConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudServiceConfiguration (string osFamily, string targetOSVersion = null, string currentOSVersion = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string osFamily, string targetOSVersion, string currentOSVersion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (osFamily As String, Optional targetOSVersion As String = null, Optional currentOSVersion As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration : string * string * string -&gt; Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration (osFamily, targetOSVersion, currentOSVersion)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="osFamily" Type="System.String" />
        <Parameter Name="targetOSVersion" Type="System.String" />
        <Parameter Name="currentOSVersion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="osFamily">プール内の仮想マシンにインストールする Azure ゲスト OS ファミリ。</param>
        <param name="targetOSVersion">プール内の仮想マシンにインストールされる Azure ゲスト OS バージョン。</param>
        <param name="currentOSVersion">現在、プール内の仮想マシンにインストールされている Azure ゲスト OS のバージョン。</param>
        <summary>
            CloudServiceConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CurrentOSVersion">
      <MemberSignature Language="C#" Value="public string CurrentOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CurrentOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property CurrentOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.CurrentOSVersion : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.CurrentOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="currentOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定、Azure ゲスト OS バージョンが現在、プール内の仮想マシンにインストールされています。
            </summary>
        <value>To be added.</value>
        <remarks>
            TargetOSVersion 異なるプールの状態がアップグレードする場合はこれがあります。 ここでは一部の仮想マシンが、targetOSVersion にあります。、アップグレード プロセス中に、currentOSVersion でいくつかあります。 すべての仮想マシンのアップグレードが currentOSVersion は targetOSVersion と同じであるに更新されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="OsFamily">
      <MemberSignature Language="C#" Value="public string OsFamily { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OsFamily" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.OsFamily" />
      <MemberSignature Language="VB.NET" Value="Public Property OsFamily As String" />
      <MemberSignature Language="F#" Value="member this.OsFamily : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.OsFamily" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osFamily")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の仮想マシンにインストールされている Azure ゲスト OS ファミリを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            指定できる値は: 2 - OS ファミリ 2、Windows Server 2008 R2 SP1 に相当します。 3-OS ファミリ 3、Windows Server 2012 に相当します。 4
            - OS ファミリ 4、Windows Server 2012 R2 に相当します。 5-OS ファミリの 5、Windows Server 2016 に相当します。 詳細については、Azure ゲスト OS リリース (https://azure.microsoft.com/documentation/articles/cloud-services-guestos-update-matrix/#releases) を参照してください。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="TargetOSVersion">
      <MemberSignature Language="C#" Value="public string TargetOSVersion { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetOSVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberSignature Language="VB.NET" Value="Public Property TargetOSVersion As String" />
      <MemberSignature Language="F#" Value="member this.TargetOSVersion : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.TargetOSVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="targetOSVersion")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはプール内の仮想マシンにインストールされている Azure ゲスト OS バージョンを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は * 指定された OS ファミリの最新のオペレーティング システムのバージョンを指定します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.CloudServiceConfiguration.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="cloudServiceConfiguration.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            オブジェクトを検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            検証が失敗した場合にスローされます。
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>