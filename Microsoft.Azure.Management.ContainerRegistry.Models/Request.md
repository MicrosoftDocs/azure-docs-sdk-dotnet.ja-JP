<Type Name="Request" FullName="Microsoft.Azure.Management.ContainerRegistry.Models.Request">
  <TypeSignature Language="C#" Value="public class Request" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Request extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerRegistry.Models.Request" />
  <TypeSignature Language="VB.NET" Value="Public Class Request" />
  <TypeSignature Language="F#" Value="type Request = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            イベントを生成する要求。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Request ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Request.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            要求クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Request (string id = null, string addr = null, string host = null, string method = null, string useragent = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, string addr, string host, string method, string useragent) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerRegistry.Models.Request.#ctor(System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional addr As String = null, Optional host As String = null, Optional method As String = null, Optional useragent As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ContainerRegistry.Models.Request : string * string * string * string * string -&gt; Microsoft.Azure.Management.ContainerRegistry.Models.Request" Usage="new Microsoft.Azure.Management.ContainerRegistry.Models.Request (id, addr, host, method, useragent)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="addr" Type="System.String" />
        <Parameter Name="host" Type="System.String" />
        <Parameter Name="method" Type="System.String" />
        <Parameter Name="useragent" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="id">イベントを開始した要求の ID。</param>
        <param name="addr">IP またはホスト名および可能性のあるイベントを開始したクライアント接続のポートです。 これは、標準の http 要求から RemoteAddr です。</param>
        <param name="host">受信要求の http ホスト ヘッダーで指定したとおり、レジストリのインスタンスの外部からアクセスできるホスト名です。</param>
        <param name="method">イベントを生成した要求メソッド。</param>
        <param name="useragent">要求のユーザー エージェント ヘッダー。</param>
        <summary>
            要求クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Addr">
      <MemberSignature Language="C#" Value="public string Addr { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Addr" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Addr" />
      <MemberSignature Language="VB.NET" Value="Public Property Addr As String" />
      <MemberSignature Language="F#" Value="member this.Addr : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Addr" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="addr")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または IP またはホスト名および可能性のあるイベントを開始したクライアント接続のポートを設定します。 これは、標準の http 要求から RemoteAddr です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Host" />
      <MemberSignature Language="VB.NET" Value="Public Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="host")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または受信した要求の http ホスト ヘッダーで指定されたレジストリ インスタンスの外部からアクセスできるホスト名を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントを開始した要求の ID を設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Method">
      <MemberSignature Language="C#" Value="public string Method { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Method" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Method" />
      <MemberSignature Language="VB.NET" Value="Public Property Method As String" />
      <MemberSignature Language="F#" Value="member this.Method : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Method" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="method")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得またはイベントを生成する要求メソッドを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Useragent">
      <MemberSignature Language="C#" Value="public string Useragent { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Useragent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ContainerRegistry.Models.Request.Useragent" />
      <MemberSignature Language="VB.NET" Value="Public Property Useragent As String" />
      <MemberSignature Language="F#" Value="member this.Useragent : string with get, set" Usage="Microsoft.Azure.Management.ContainerRegistry.Models.Request.Useragent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerRegistry</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="useragent")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または、ユーザー エージェント要求のヘッダーを設定します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>