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
            <span data-ttu-id="81648-101">RemoteExceptions の WebHDFS 定義に基づく data Lake Store filesystem 例外。</span><span class="sxs-lookup"><span data-stu-id="81648-101">Data Lake Store filesystem exception based on the WebHDFS definition for RemoteExceptions.</span></span> <span data-ttu-id="81648-102">これは、WebHDFS 'すべて' 例外のキャッチ</span><span class="sxs-lookup"><span data-stu-id="81648-102">This is a WebHDFS 'catch all' exception</span></span>
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
            <span data-ttu-id="81648-103">AdlsRemoteException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81648-103">Initializes a new instance of the AdlsRemoteException class.</span></span>
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
        <param name="javaClassName"><span data-ttu-id="81648-104">フル パッケージのクラス名 'java.lang.IllegalArgumentException' など、スローされる例外。</span><span class="sxs-lookup"><span data-stu-id="81648-104">the full class package name for the exception thrown, such as 'java.lang.IllegalArgumentException'.</span></span></param>
        <param name="message"><span data-ttu-id="81648-105">など、スローされた例外に関連付けられたメッセージ ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。</span><span class="sxs-lookup"><span data-stu-id="81648-105">the message associated with the exception that was thrown, such as 'Invalid value for webhdfs parameter "permission":...'.</span></span></param>
        <summary>
            <span data-ttu-id="81648-106">AdlsRemoteException クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="81648-106">Initializes a new instance of the AdlsRemoteException class.</span></span>
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
            <span data-ttu-id="81648-107">例外がスローされた場合、'java.lang.IllegalArgumentException' などのクラスの完全パッケージ名を取得します。</span><span class="sxs-lookup"><span data-stu-id="81648-107">Gets the full class package name for the exception thrown, such as 'java.lang.IllegalArgumentException'.</span></span>
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
            <span data-ttu-id="81648-108">メッセージを取得しますように、スローされた例外に関連付けられている ' webhdfs パラメーター「アクセス許可」に無効な値:...' です。</span><span class="sxs-lookup"><span data-stu-id="81648-108">Gets the message associated with the exception that was thrown, such as 'Invalid value for webhdfs parameter "permission":...'.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>