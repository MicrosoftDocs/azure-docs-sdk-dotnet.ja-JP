<Type Name="AuthorizationFailedException" FullName="Microsoft.Azure.Relay.AuthorizationFailedException">
  <TypeSignature Language="C#" Value="public class AuthorizationFailedException : Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable beforefieldinit AuthorizationFailedException extends Microsoft.Azure.Relay.RelayException" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Relay.AuthorizationFailedException" />
  <TypeSignature Language="VB.NET" Value="Public Class AuthorizationFailedException&#xA;Inherits RelayException" />
  <TypeSignature Language="F#" Value="type AuthorizationFailedException = class&#xA;    inherit RelayException" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Relay.RelayException</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            認証の試行が失敗したときに発生する例外。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationFailedException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.AuthorizationFailedException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            
                      <see cref="T:Microsoft.Azure.Relay.AuthorizationFailedException" /> クラスの新しいインスタンスを作成します。
</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationFailedException (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.AuthorizationFailedException.#ctor(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.AuthorizationFailedException : string -&gt; Microsoft.Azure.Relay.AuthorizationFailedException" Usage="new Microsoft.Azure.Relay.AuthorizationFailedException message" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">エラーを説明するメッセージ。 </param>
        <summary>
            新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.AuthorizationFailedException" />指定したエラー メッセージを使用します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected AuthorizationFailedException (System.Runtime.Serialization.SerializationInfo info, System.Runtime.Serialization.StreamingContext context);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class System.Runtime.Serialization.SerializationInfo info, valuetype System.Runtime.Serialization.StreamingContext context) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.AuthorizationFailedException.#ctor(System.Runtime.Serialization.SerializationInfo,System.Runtime.Serialization.StreamingContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New (info As SerializationInfo, context As StreamingContext)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.AuthorizationFailedException : System.Runtime.Serialization.SerializationInfo * System.Runtime.Serialization.StreamingContext -&gt; Microsoft.Azure.Relay.AuthorizationFailedException" Usage="new Microsoft.Azure.Relay.AuthorizationFailedException (info, context)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="info" Type="System.Runtime.Serialization.SerializationInfo" />
        <Parameter Name="context" Type="System.Runtime.Serialization.StreamingContext" />
      </Parameters>
      <Docs>
        <param name="info">スローされている例外に関するシリアル化済みオブジェクト データを保持している <see cref="T:System.Runtime.Serialization.SerializationInfo" />。 </param>
        <param name="context">転送元または転送先についてのコンテキスト情報を含む <see cref="T:System.Runtime.Serialization.StreamingContext" /> です。 </param>
        <summary>
            新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.AuthorizationFailedException" />シリアル化されたデータを持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AuthorizationFailedException (string message, Exception innerException);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string message, class System.Exception innerException) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Relay.AuthorizationFailedException.#ctor(System.String,System.Exception)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (message As String, innerException As Exception)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Relay.AuthorizationFailedException : string * Exception -&gt; Microsoft.Azure.Relay.AuthorizationFailedException" Usage="new Microsoft.Azure.Relay.AuthorizationFailedException (message, innerException)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Relay</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="innerException" Type="System.Exception" />
      </Parameters>
      <Docs>
        <param name="message">エラーを説明するメッセージ。</param>
        <param name="innerException">現在の例外の原因となった例外。</param>
        <summary>
            新しいインスタンスを作成、<see cref="T:Microsoft.Azure.Relay.AuthorizationFailedException" />指定したエラー メッセージおよびこの例外の原因となった内部例外への参照を持つクラス。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>