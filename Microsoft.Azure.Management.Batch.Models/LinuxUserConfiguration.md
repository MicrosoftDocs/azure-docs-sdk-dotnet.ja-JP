<Type Name="LinuxUserConfiguration" FullName="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration">
  <TypeSignature Language="C#" Value="public class LinuxUserConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit LinuxUserConfiguration extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class LinuxUserConfiguration" />
  <TypeSignature Language="F#" Value="type LinuxUserConfiguration = class" />
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
            プロパティは、Linux ノード上のユーザー アカウントを作成するために使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxUserConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            LinuxUserConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public LinuxUserConfiguration (Nullable&lt;int&gt; uid = null, Nullable&lt;int&gt; gid = null, string sshPrivateKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; uid, valuetype System.Nullable`1&lt;int32&gt; gid, string sshPrivateKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional uid As Nullable(Of Integer) = null, Optional gid As Nullable(Of Integer) = null, Optional sshPrivateKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration : Nullable&lt;int&gt; * Nullable&lt;int&gt; * string -&gt; Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration" Usage="new Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration (uid, gid, sshPrivateKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="uid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="gid" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="sshPrivateKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="uid">ユーザー アカウントのユーザー ID。</param>
        <param name="gid">ユーザー アカウントのグループ ID。</param>
        <param name="sshPrivateKey">ユーザー アカウントの SSH 秘密キーです。</param>
        <summary>
            LinuxUserConfiguration クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Gid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Gid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Gid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Gid" />
      <MemberSignature Language="VB.NET" Value="Public Property Gid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Gid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Gid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="gid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントのグループ ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            同時にまたはまったくない、uid および gid プロパティを指定してください。 基になる動作を指定しない場合、システムは、gid を取得します。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPrivateKey">
      <MemberSignature Language="C#" Value="public string SshPrivateKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPrivateKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.SshPrivateKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPrivateKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPrivateKey : string with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.SshPrivateKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sshPrivateKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントの SSH 秘密キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            秘密キーがパスワードで保護することはできません。 秘密キーは自動的にプールの enableInterNodeCommunication プロパティが true (これは無視されます enableInterNodeCommunication が false の場合) の場合は、Linux プール内のノード間で SSH の非対称キーに基づく認証を構成する使用されます。 これは、キーのペアをユーザーの .ssh ディレクトリに配置することで実行します。 存在しない場合 (ユーザーの .ssh ディレクトリの変更は行われません) ノード間で指定すると、パスワードのない SSH が構成されていません。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Uid">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; Uid { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; Uid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Uid" />
      <MemberSignature Language="VB.NET" Value="Public Property Uid As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.Uid : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.Management.Batch.Models.LinuxUserConfiguration.Uid" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="uid")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはユーザー アカウントのユーザー ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            同時にまたはまったくない、uid および gid プロパティを指定してください。 基になる動作を指定しない場合、システムは、uid を取得します。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>