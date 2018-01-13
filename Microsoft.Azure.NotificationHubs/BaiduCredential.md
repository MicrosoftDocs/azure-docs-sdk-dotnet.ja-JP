<Type Name="BaiduCredential" FullName="Microsoft.Azure.NotificationHubs.BaiduCredential">
  <TypeSignature Language="C#" Value="public class BaiduCredential : Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BaiduCredential extends Microsoft.Azure.NotificationHubs.PnsCredential" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.BaiduCredential" />
  <TypeSignature Language="VB.NET" Value="Public Class BaiduCredential&#xA;Inherits PnsCredential" />
  <TypeSignature Language="F#" Value="type BaiduCredential = class&#xA;    inherit PnsCredential" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.NotificationHubs.PnsCredential</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="BaiduCredential", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Baidu 資格情報を表します
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduCredential ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public BaiduCredential (string baiduApiKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string baiduApiKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baiduApiKey As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.NotificationHubs.BaiduCredential : string -&gt; Microsoft.Azure.NotificationHubs.BaiduCredential" Usage="new Microsoft.Azure.NotificationHubs.BaiduCredential baiduApiKey" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baiduApiKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="baiduApiKey">Baidu API キー。</param>
        <summary>
            <see cref="T:Microsoft.Azure.NotificationHubs.BaiduCredential" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduApiKey">
      <MemberSignature Language="C#" Value="public string BaiduApiKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduApiKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduApiKey" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduApiKey As String" />
      <MemberSignature Language="F#" Value="member this.BaiduApiKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduApiKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Baidu API キーを設定します。
            </summary>
        <value>
            Baidu API キー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduEndPoint">
      <MemberSignature Language="C#" Value="public string BaiduEndPoint { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduEndPoint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduEndPoint" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduEndPoint As String" />
      <MemberSignature Language="F#" Value="member this.BaiduEndPoint : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduEndPoint" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Baidu 終了位置を設定します。
            </summary>
        <value>
            Baidu の終点。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaiduSecretKey">
      <MemberSignature Language="C#" Value="public string BaiduSecretKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string BaiduSecretKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduSecretKey" />
      <MemberSignature Language="VB.NET" Value="Public Property BaiduSecretKey As String" />
      <MemberSignature Language="F#" Value="member this.BaiduSecretKey : string with get, set" Usage="Microsoft.Azure.NotificationHubs.BaiduCredential.BaiduSecretKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            取得または Baidu 秘密キーを設定します。
            </summary>
        <value>
            Baidu のシークレット キー。
            </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="baiduCredential.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">このインスタンスと比較する <see cref="T:System.Object" />。</param>
        <summary>
            指定するかどうか、指定した<see cref="T:System.Object" />がこのインスタンスと等しい。
            </summary>
        <returns>
          <c>true</c>場合、指定した<see cref="T:System.Object" />、それ以外のこのインスタンスと等しい<c>false</c>です。
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="baiduCredential.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            このインスタンスのハッシュ コードを返します。
            </summary>
        <returns>
            このインスタンスのハッシュ コード。ハッシュ アルゴリズムでもハッシュ テーブルのようなデータ構造でも使用できるもの。 
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate (bool allowLocalMockPns);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate(bool allowLocalMockPns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.BaiduCredential.OnValidate(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate (allowLocalMockPns As Boolean)" />
      <MemberSignature Language="F#" Value="override this.OnValidate : bool -&gt; unit" Usage="baiduCredential.OnValidate allowLocalMockPns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="allowLocalMockPns" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="allowLocalMockPns">ローカルのモック PNS; を許可する場合は trueそれ以外の場合は false です。</param>
        <summary>
            資格情報を検証します。
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Runtime.Serialization.InvalidDataContractException" />
      </Docs>
    </Member>
  </Members>
</Type>