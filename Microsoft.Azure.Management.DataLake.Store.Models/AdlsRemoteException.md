<Type Name="AdlsRemoteException" FullName="Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException">
  <TypeSignature Language="C#" Value="public class AdlsRemoteException" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AdlsRemoteException extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" />
  <TypeSignature Language="VB.NET" Value="Public Class AdlsRemoteException" />
  <TypeSignature Language="F#" Value="type AdlsRemoteException = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            RemoteExceptions の WebHDFS 定義に基づく data Lake Store filesystem 例外。 これは、WebHDFS 'すべて' 例外のキャッチ
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsRemoteException ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            AdlsRemoteException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AdlsRemoteException (string javaClassName = null, string message = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string javaClassName, string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional javaClassName As String = null, Optional message As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException : string * string -&gt; Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException" Usage="new Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException (javaClassName, message)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="javaClassName" Type="System.String" />
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="javaClassName">フル パッケージのクラス名 'java.lang.IllegalArgumentException' など、スローされる例外。</param>
        <param name="message">など、スローされた例外に関連付けられたメッセージ ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。</param>
        <summary>
            AdlsRemoteException クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaClassName">
      <MemberSignature Language="C#" Value="public string JavaClassName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaClassName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.JavaClassName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaClassName As String" />
      <MemberSignature Language="F#" Value="member this.JavaClassName : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.JavaClassName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="javaClassName")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            例外がスローされた場合、'java.lang.IllegalArgumentException' などのクラスの完全パッケージ名を取得します。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.Management.DataLake.Store.Models.AdlsRemoteException.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataLake.Store</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="message")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            メッセージを取得しますように、スローされた例外に関連付けられている ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>