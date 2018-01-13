<Type Name="ComputeNodeUser" FullName="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser">
  <TypeSignature Language="C#" Value="public class ComputeNodeUser" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ComputeNodeUser extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
  <TypeSignature Language="VB.NET" Value="Public Class ComputeNodeUser" />
  <TypeSignature Language="F#" Value="type ComputeNodeUser = class" />
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
            コンピューティング ノードで RDP または SSH アクセスのユーザー アカウント。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeUser ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.#ctor" />
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
            ComputeNodeUser クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ComputeNodeUser (string name, Nullable&lt;bool&gt; isAdmin = null, Nullable&lt;DateTime&gt; expiryTime = null, string password = null, string sshPublicKey = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, valuetype System.Nullable`1&lt;bool&gt; isAdmin, valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; expiryTime, string password, string sshPublicKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.#ctor(System.String,System.Nullable{System.Boolean},System.Nullable{System.DateTime},System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (name As String, Optional isAdmin As Nullable(Of Boolean) = null, Optional expiryTime As Nullable(Of DateTime) = null, Optional password As String = null, Optional sshPublicKey As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser : string * Nullable&lt;bool&gt; * Nullable&lt;DateTime&gt; * string * string -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" Usage="new Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser (name, isAdmin, expiryTime, password, sshPublicKey)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="isAdmin" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="expiryTime" Type="System.Nullable&lt;System.DateTime&gt;" />
        <Parameter Name="password" Type="System.String" />
        <Parameter Name="sshPublicKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">アカウントのユーザー名。</param>
        <param name="isAdmin">かどうか、アカウント コンピューティング ノード上で管理者である必要があります。</param>
        <param name="expiryTime">アカウントが期限切れになる時刻。</param>
        <param name="password">アカウントのパスワードです。</param>
        <param name="sshPublicKey">コンピューティング ノードにリモート ログインに使用できる SSH 公開キー。</param>
        <summary>
            ComputeNodeUser クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpiryTime">
      <MemberSignature Language="C#" Value="public Nullable&lt;DateTime&gt; ExpiryTime { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype System.DateTime&gt; ExpiryTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.ExpiryTime" />
      <MemberSignature Language="VB.NET" Value="Public Property ExpiryTime As Nullable(Of DateTime)" />
      <MemberSignature Language="F#" Value="member this.ExpiryTime : Nullable&lt;DateTime&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.ExpiryTime" />
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
    <Member MemberName="IsAdmin">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsAdmin { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsAdmin" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.IsAdmin" />
      <MemberSignature Language="VB.NET" Value="Public Property IsAdmin As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsAdmin : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.IsAdmin" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isAdmin")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または計算ノードの管理者である必要があります、アカウントかどうかを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>
            既定値は false です。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはアカウントのユーザー名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.Password" />
      <MemberSignature Language="VB.NET" Value="Public Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.Password" />
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
            パスワードが Windows ノード ('cloudServiceConfiguration' で作成またはで 'virtualMachineConfiguration' Windows イメージ参照を使用して作成されたもの) 必要です。 Linux 計算ノードの場合は、パスワードが必要に応じて sshPublicKey プロパティと共に指定することができます。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="SshPublicKey">
      <MemberSignature Language="C#" Value="public string SshPublicKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SshPublicKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.SshPublicKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SshPublicKey As String" />
      <MemberSignature Language="F#" Value="member this.SshPublicKey : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.SshPublicKey" />
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
            公開キーが OpenSSH エンコーディングと互換性があるし、base 64 エンコードします。 このプロパティは、Linux ノードに対してのみ指定できます。 Windows ノードに対して指定されている場合、バッチ サービスは要求を拒否;REST API を直接呼び出すが、HTTP ステータス コードは 400 (Bad Request) がします。
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="computeNodeUser.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
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