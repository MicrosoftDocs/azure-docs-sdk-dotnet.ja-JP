<Type Name="FileServer" FullName="Microsoft.Azure.Management.BatchAI.Models.FileServer">
  <TypeSignature Language="C#" Value="public class FileServer : Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit FileServer extends Microsoft.Azure.Management.BatchAI.Models.Resource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.BatchAI.Models.FileServer" />
  <TypeSignature Language="VB.NET" Value="Public Class FileServer&#xA;Inherits Resource" />
  <TypeSignature Language="F#" Value="type FileServer = class&#xA;    inherit Resource" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.BatchAI.Models.Resource</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Rest.Serialization.JsonTransformation</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            ファイル サーバーに関する情報が含まれています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            FileServer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public FileServer (string id = null, string name = null, string type = null, string location = null, System.Collections.Generic.IDictionary&lt;string,string&gt; tags = null, string vmSize = null, Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration = null, Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks = null, Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet = null, Microsoft.Azure.Management.BatchAI.Models.MountSettings mountSettings = null, Nullable&lt;DateTime&gt; provisioningStateTransitionTime = null, Nullable&lt;DateTime&gt; creationTime = null, Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState provisioningState = Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState.Creating);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string name, string type, string location, class System.Collections.Generic.IDictionary`2&lt;string, string&gt; tags, string vmSize, class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration sshConfiguration, class Microsoft.Azure.Management.BatchAI.Models.DataDisks dataDisks, class Microsoft.Azure.Management.BatchAI.Models.ResourceId subnet, class Microsoft.Azure.Management.BatchAI.Models.MountSettings mountSettings, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; provisioningStateTransitionTime, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; creationTime, valuetype Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState provisioningState) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.#ctor(System.String,System.String,System.String,System.String,System.Collections.Generic.IDictionary{System.String,System.String},System.String,Microsoft.Azure.Management.BatchAI.Models.SshConfiguration,Microsoft.Azure.Management.BatchAI.Models.DataDisks,Microsoft.Azure.Management.BatchAI.Models.ResourceId,Microsoft.Azure.Management.BatchAI.Models.MountSettings,System.Nullable{System.DateTime},System.Nullable{System.DateTime},Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.BatchAI.Models.FileServer : string * string * string * string * System.Collections.Generic.IDictionary&lt;string, string&gt; * string * Microsoft.Azure.Management.BatchAI.Models.SshConfiguration * Microsoft.Azure.Management.BatchAI.Models.DataDisks * Microsoft.Azure.Management.BatchAI.Models.ResourceId * Microsoft.Azure.Management.BatchAI.Models.MountSettings * Nullable&lt;DateTime&gt; * Nullable&lt;DateTime&gt; * Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState -&gt; Microsoft.Azure.Management.BatchAI.Models.FileServer" Usage="new Microsoft.Azure.Management.BatchAI.Models.FileServer (id, name, type, location, tags, vmSize, sshConfiguration, dataDisks, subnet, mountSettings, provisioningStateTransitionTime, creationTime, provisioningState)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="type" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="tags" Type="System.Collections.Generic.IDictionary&lt;System.String,System.String&gt;" />
        <Parameter Name="vmSize" Type="System.String" />
        <Parameter Name="sshConfiguration" Type="Microsoft.Azure.Management.BatchAI.Models.SshConfiguration" />
        <Parameter Name="dataDisks" Type="Microsoft.Azure.Management.BatchAI.Models.DataDisks" />
        <Parameter Name="subnet" Type="Microsoft.Azure.Management.BatchAI.Models.ResourceId" />
        <Parameter Name="mountSettings" Type="Microsoft.Azure.Management.BatchAI.Models.MountSettings" />
        <Parameter Name="provisioningStateTransitionTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="creationTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="provisioningState" Type="Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState" />
      </Parameters>
      <Docs>
        <param name="id">リソースの ID</param>
        <param name="name">リソースの名前</param>
        <param name="type">リソースの種類</param>
        <param name="location">リソースの場所</param>
        <param name="tags">リソースのタグ</param>
        <param name="vmSize">ファイル サーバーの仮想マシンのサイズ。</param>
        <param name="sshConfiguration">ファイル サーバーの SSH 設定します。</param>
        <param name="dataDisks">ファイル サーバーの作成とデータ ディスクの設定です。</param>
        <param name="subnet">サブネットの識別子を指定します。</param>
        <param name="mountSettings">ファイル サーバーの詳細です。</param>
        <param name="provisioningStateTransitionTime">状態が変更された時刻。</param>
        <param name="creationTime">ファイル サーバーが作成された時刻。</param>
        <param name="provisioningState">ファイル サーバーのプロビジョニングの状態を指定します。</param>
        <summary>
            FileServer クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreationTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; CreationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; CreationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.CreationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreationTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.CreationTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.CreationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.creationTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル サーバーの作成日時を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataDisks">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.DataDisks DataDisks" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.DataDisks" />
      <MemberSignature Language="VB.NET" Value="Public Property DataDisks As DataDisks" />
      <MemberSignature Language="F#" Value="member this.DataDisks : Microsoft.Azure.Management.BatchAI.Models.DataDisks with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.DataDisks" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.dataDisks")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.DataDisks</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル サーバーの作成とデータ ディスクの設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MountSettings">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.MountSettings MountSettings { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.MountSettings MountSettings" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.MountSettings" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MountSettings As MountSettings" />
      <MemberSignature Language="F#" Value="member this.MountSettings : Microsoft.Azure.Management.BatchAI.Models.MountSettings" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.MountSettings" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.mountSettings")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.MountSettings</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            ファイル サーバーの詳細を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As FileServerProvisioningState" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningState")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.FileServerProvisioningState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得では、ファイル サーバーのプロビジョニングの状態を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            使用可能な値: 作成、ファイル サーバーの作成中です。
            更新 - ファイル サーバーの作成が受け付けられるし、は更新を取得します。 削除すると、ユーザーがファイル サーバーが削除されることを要求し、は、削除されている処理中です。
            失敗しました - 指定したエラー コードとファイル サーバーの作成に失敗しました。 エラー コードに関する詳細については、[メッセージ] フィールドで指定されます。 成功 - ファイル サーバーの作成は成功しました。
            使用可能な値が含まれます: '作成中'、'更新'、'削除'、'成功'、'失敗'
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningStateTransitionTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ProvisioningStateTransitionTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ProvisioningStateTransitionTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningStateTransitionTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningStateTransitionTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ProvisioningStateTransitionTime : Nullable&lt;DateTime&gt;" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.ProvisioningStateTransitionTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.provisioningStateTransitionTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            状態が変更された日時を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SshConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.SshConfiguration SshConfiguration" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.SshConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Property SshConfiguration As SshConfiguration" />
      <MemberSignature Language="F#" Value="member this.SshConfiguration : Microsoft.Azure.Management.BatchAI.Models.SshConfiguration with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.SshConfiguration" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.sshConfiguration")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.SshConfiguration</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル サーバーの SSH の設定を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Subnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.BatchAI.Models.ResourceId Subnet" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.Subnet" />
      <MemberSignature Language="VB.NET" Value="Public Property Subnet As ResourceId" />
      <MemberSignature Language="F#" Value="member this.Subnet : Microsoft.Azure.Management.BatchAI.Models.ResourceId with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.Subnet" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.subnet")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.BatchAI.Models.ResourceId</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または設定は、サブネットの識別子を指定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.BatchAI.Models.FileServer.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="fileServer.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
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
    <Member MemberName="VmSize">
      <MemberSignature Language="C#" Value="public string VmSize { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VmSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.BatchAI.Models.FileServer.VmSize" />
      <MemberSignature Language="VB.NET" Value="Public Property VmSize As String" />
      <MemberSignature Language="F#" Value="member this.VmSize : string with get, set" Usage="Microsoft.Azure.Management.BatchAI.Models.FileServer.VmSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.BatchAI</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties.vmSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはファイル サーバーの仮想マシンのサイズを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            仮想マシン Marketplace からファイル サーバーの利用可能な VM サイズについては、仮想マシン (Linux) のサイズを参照してください。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>