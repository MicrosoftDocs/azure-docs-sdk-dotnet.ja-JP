<Type Name="HandlerMapping" FullName="Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping">
  <TypeSignature Language="C#" Value="public class HandlerMapping" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit HandlerMapping extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping" />
  <TypeSignature Language="VB.NET" Value="Public Class HandlerMapping" />
  <TypeSignature Language="F#" Value="type HandlerMapping = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5f0fb-101">IIS のハンドラー マッピングはどのハンドラーで処理する HTTP 要求を特定の拡張子で定義するために使用します。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-101">The IIS handler mappings used to define which handler processes HTTP requests with certain extension.</span></span>
            <span data-ttu-id="5f0fb-102">たとえば、\*.php 拡張子を持つすべての HTTP 要求を処理する cgi.exe プロセスの構成に使用されます。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-102">For example, it is used to configure php-cgi.exe process to handle all HTTP requests with \*.php extension.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HandlerMapping ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5f0fb-103">HandlerMapping クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-103">Initializes a new instance of the HandlerMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public HandlerMapping (string extension = null, string scriptProcessor = null, string arguments = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string extension, string scriptProcessor, string arguments) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.#ctor(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional extension As String = null, Optional scriptProcessor As String = null, Optional arguments As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping : string * string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping" Usage="new Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping (extension, scriptProcessor, arguments)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="extension" Type="System.String" />
        <Parameter Name="scriptProcessor" Type="System.String" />
        <Parameter Name="arguments" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="extension"><span data-ttu-id="5f0fb-104">この拡張機能での要求は、指定された FastCGI アプリケーションを使用して処理されます。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-104">Requests with this extension will be handled using the specified FastCGI application.</span></span></param>
        <param name="scriptProcessor"><span data-ttu-id="5f0fb-105">FastCGI アプリケーションへの絶対パス。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-105">The absolute path to the FastCGI application.</span></span></param>
        <param name="arguments"><span data-ttu-id="5f0fb-106">スクリプト プロセッサに渡されるコマンドライン引数。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-106">Command-line arguments to be passed to the script processor.</span></span></param>
        <summary>
            <span data-ttu-id="5f0fb-107">HandlerMapping クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-107">Initializes a new instance of the HandlerMapping class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Arguments">
      <MemberSignature Language="C#" Value="public string Arguments { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Arguments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.Arguments" />
      <MemberSignature Language="VB.NET" Value="Public Property Arguments As String" />
      <MemberSignature Language="F#" Value="member this.Arguments : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.Arguments" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="arguments")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f0fb-108">取得またはスクリプト プロセッサに渡されるコマンドライン引数を設定します。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-108">Gets or sets command-line arguments to be passed to the script processor.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Extension">
      <MemberSignature Language="C#" Value="public string Extension { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Extension" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.Extension" />
      <MemberSignature Language="VB.NET" Value="Public Property Extension As String" />
      <MemberSignature Language="F#" Value="member this.Extension : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.Extension" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="extension")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f0fb-109">この要求の設定を取得または拡張機能は、指定された FastCGI アプリケーションを使用して処理されます。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-109">Gets or sets requests with this extension will be handled using the specified FastCGI application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ScriptProcessor">
      <MemberSignature Language="C#" Value="public string ScriptProcessor { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ScriptProcessor" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.ScriptProcessor" />
      <MemberSignature Language="VB.NET" Value="Public Property ScriptProcessor As String" />
      <MemberSignature Language="F#" Value="member this.ScriptProcessor : string with get, set" Usage="Microsoft.Azure.Management.AppService.Fluent.Models.HandlerMapping.ScriptProcessor" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="scriptProcessor")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5f0fb-110">取得または FastCGI アプリケーションに絶対パスを設定します。</span><span class="sxs-lookup"><span data-stu-id="5f0fb-110">Gets or sets the absolute path to the FastCGI application.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>