<Type Name="SharedAccessAuthorizationRule" FullName="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule">
  <TypeSignature Language="C#" Value="public class SharedAccessAuthorizationRule : Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SharedAccessAuthorizationRule extends Microsoft.ServiceBus.Messaging.AuthorizationRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" />
  <TypeSignature Language="VB.NET" Value="Public Class SharedAccessAuthorizationRule&#xA;Inherits AuthorizationRule" />
  <TypeSignature Language="F#" Value="type SharedAccessAuthorizationRule = class&#xA;    inherit AuthorizationRule" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceBus.Messaging.AuthorizationRule</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.Runtime.Serialization.DataContract(Name="SharedAccessAuthorizationRule", Namespace="http://schemas.microsoft.com/netservices/2010/10/servicebus/connect")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>共有アクセス操作の承認規則を定義します。</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName">承認規則のキー名。</param>
        <param name="rights">権限の一覧。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName">承認規則のキー名。</param>
        <param name="primaryKey">承認規則の主キー。</param>
        <param name="rights">権限の一覧。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessAuthorizationRule (string keyName, string primaryKey, string secondaryKey, System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; rights);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string keyName, string primaryKey, string secondaryKey, class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; rights) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.#ctor(System.String,System.String,System.String,System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (keyName As String, primaryKey As String, secondaryKey As String, rights As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule : string * string * string * seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" Usage="new Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule (keyName, primaryKey, secondaryKey, rights)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="keyName" Type="System.String" />
        <Parameter Name="primaryKey" Type="System.String" />
        <Parameter Name="secondaryKey" Type="System.String" />
        <Parameter Name="rights" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="keyName">承認規則のキー名。</param>
        <param name="primaryKey">承認規則の主キー。</param>
        <param name="secondaryKey">承認規則のセカンダリ キー。</param>
        <param name="rights">権限の一覧。</param>
        <summary><see cref="T:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule" /> クラスの新しいインスタンスを初期化します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Equals">
      <MemberSignature Language="C#" Value="public override bool Equals (object obj);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance bool Equals(object obj) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Equals(System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function Equals (obj As Object) As Boolean" />
      <MemberSignature Language="F#" Value="override this.Equals : obj -&gt; bool" Usage="sharedAccessAuthorizationRule.Equals obj" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="obj" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="obj">現在のオブジェクトと比較するオブジェクト。</param>
        <summary>指定したオブジェクトが、現在のオブジェクトと等しいかどうかを判断します。</summary>
        <returns>指定したオブジェクトが現在のオブジェクトと等しい場合は true。それ以外の場合は false です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GenerateRandomKey">
      <MemberSignature Language="C#" Value="public static string GenerateRandomKey ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GenerateRandomKey() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GenerateRandomKey () As String" />
      <MemberSignature Language="F#" Value="static member GenerateRandomKey : unit -&gt; string" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GenerateRandomKey " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>承認規則のランダムなキーを生成します。</summary>
        <returns>承認規則のランダムなキーです。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHashCode">
      <MemberSignature Language="C#" Value="public override int GetHashCode ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance int32 GetHashCode() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.GetHashCode" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function GetHashCode () As Integer" />
      <MemberSignature Language="F#" Value="override this.GetHashCode : unit -&gt; int" Usage="sharedAccessAuthorizationRule.GetHashCode " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>このインスタンスのハッシュ コードを返します。</summary>
        <returns>対象のインスタンスのハッシュ コード。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="KeyName">
      <MemberSignature Language="C#" Value="public override sealed string KeyName { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string KeyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberSignature Language="VB.NET" Value="Public Overrides NotOverridable Property KeyName As String" />
      <MemberSignature Language="F#" Value="member this.KeyName : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.KeyName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または承認規則のキー名を設定します。</summary>
        <value>承認規則のキー名。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnValidate">
      <MemberSignature Language="C#" Value="protected override void OnValidate ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void OnValidate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.OnValidate" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub OnValidate ()" />
      <MemberSignature Language="F#" Value="override this.OnValidate : unit -&gt; unit" Usage="sharedAccessAuthorizationRule.OnValidate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>承認規則の有効性を確認します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PrimaryKey">
      <MemberSignature Language="C#" Value="public string PrimaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PrimaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property PrimaryKey As String" />
      <MemberSignature Language="F#" Value="member this.PrimaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.PrimaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得または承認規則の主キーを設定します。</summary>
        <value>承認規則の主キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SecondaryKey">
      <MemberSignature Language="C#" Value="public string SecondaryKey { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SecondaryKey" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberSignature Language="VB.NET" Value="Public Property SecondaryKey As String" />
      <MemberSignature Language="F#" Value="member this.SecondaryKey : string with get, set" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.SecondaryKey" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>取得またはセカンダリ キーを承認規則を設定します。</summary>
        <value>承認規則のセカンダリ キー。</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Serializer">
      <MemberSignature Language="C#" Value="public static readonly System.Runtime.Serialization.DataContractSerializer Serializer;" />
      <MemberSignature Language="ILAsm" Value=".field public static initonly class System.Runtime.Serialization.DataContractSerializer Serializer" />
      <MemberSignature Language="DocId" Value="F:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberSignature Language="VB.NET" Value="Public Shared ReadOnly Serializer As DataContractSerializer " />
      <MemberSignature Language="F#" Value=" staticval mutable Serializer : System.Runtime.Serialization.DataContractSerializer" Usage="Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.Serializer" />
      <MemberType>Field</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Runtime.Serialization.DataContractSerializer</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            SharedAccessAuthorizationRule 型のオブジェクトのシリアライザー。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ValidateRights">
      <MemberSignature Language="C#" Value="protected override void ValidateRights (System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; value);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void ValidateRights(class System.Collections.Generic.IEnumerable`1&lt;valuetype Microsoft.ServiceBus.Messaging.AccessRights&gt; value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.SharedAccessAuthorizationRule.ValidateRights(System.Collections.Generic.IEnumerable{Microsoft.ServiceBus.Messaging.AccessRights})" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub ValidateRights (value As IEnumerable(Of AccessRights))" />
      <MemberSignature Language="F#" Value="override this.ValidateRights : seq&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt; -&gt; unit" Usage="sharedAccessAuthorizationRule.ValidateRights value" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="value" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.ServiceBus.Messaging.AccessRights&gt;" />
      </Parameters>
      <Docs>
        <param name="value">確認へのアクセス権。</param>
        <summary>指定したアクセス権の有効性を確認します。</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>