<Type Name="NodeUpdateUserParameter" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter">
  <TypeSignature Language="C#" Value="public class NodeUpdateUserParameter" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeUpdateUserParameter extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeUpdateUserParameter" />
  <TypeSignature Language="F#" Value="type NodeUpdateUserParameter = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            一連のノード上のユーザー アカウントに変更します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeUpdateUserParameter ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            NodeUpdateUserParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeUpdateUserParameter (string password = null, Nullable&lt;DateTime&gt; expiryTime = null, string sshPublicKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string password, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, string sshPublicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.#ctor(System.String,System.Nullable{System.DateTime},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional password As String = null, Optional expiryTime As Nullable(Of DateTime) = null, Optional sshPublicKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter : string * Nullable&lt;DateTime&gt; * string -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter (password, expiryTime, sshPublicKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="sshPublicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="password">アカウントのパスワードです。</param>
        <param name="expiryTime">アカウントが期限切れになる時刻。</param>
        <param name="sshPublicKey">コンピューティング ノードにリモート ログインに使用できる SSH 公開キー。</param>
        <summary>
            NodeUpdateUserParameter クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.ExpiryTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="expiryTime")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.DateTime&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウントが期限切れになる時間を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            省略した場合、既定では、現在の時刻から 1 日です。 Linux コンピューティング ノード、expiryTime が有効桁数は最大で 1 日です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.Password" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="password")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウントのパスワードを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            パスワードが Windows ノード ('cloudServiceConfiguration' で作成またはで 'virtualMachineConfiguration' Windows イメージ参照を使用して作成されたもの) 必要です。 Linux 計算ノードの場合は、パスワードが必要に応じて sshPublicKey プロパティと共に指定することができます。 省略した場合は、既存のパスワードが削除されます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter.SshPublicKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="sshPublicKey")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはコンピューティング ノードにリモート ログインに使用できる SSH 公開キーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            公開キーが OpenSSH エンコーディングと互換性があるし、base 64 エンコードします。 このプロパティは、Linux ノードに対してのみ指定できます。 Windows ノードに対して指定されている場合、バッチ サービスは要求を拒否;REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。 省略した場合は、既存の SSH 公開キーが削除されます。
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>