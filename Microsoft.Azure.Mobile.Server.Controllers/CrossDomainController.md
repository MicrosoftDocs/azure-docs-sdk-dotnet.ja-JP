<Type Name="CrossDomainController" FullName="Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController">
  <TypeSignature Language="C#" Value="public class CrossDomainController : System.Web.Http.ApiController" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CrossDomainController extends System.Web.Http.ApiController" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController" />
  <TypeSignature Language="VB.NET" Value="Public Class CrossDomainController&#xA;Inherits ApiController" />
  <TypeSignature Language="F#" Value="type CrossDomainController = class&#xA;    inherit ApiController" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Web.Http.ApiController</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Mobile.Server.Config.MobileAppController</AttributeName>
    </Attribute>
    <Attribute>
      <AttributeName>System.Web.Http.Description.ApiExplorerSettings(IgnoreApi=true)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            このコント ローラーでは、古いブラウザーのドメイン間の通信をサポートするファイルを返します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CrossDomainController ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Bridge">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt; Bridge (string origin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.IHttpActionResult&gt; Bridge(string origin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.Bridge(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Bridge (origin As String) As Task(Of IHttpActionResult)" />
      <MemberSignature Language="F#" Value="member this.Bridge : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;" Usage="crossDomainController.Bridge origin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController/&lt;Bridge&gt;d__2))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.AllowAnonymous</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.HttpGet</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="origin" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="origin">配信元を確認するには</param>
        <summary>
             ホストされている場合、A ページ、 <c>iframe</c>、許可されたオリジンから postMessage のメッセージを受け入れるし、ランタイムに同じドメインの ajax 要求として転送されます。 これは必要、 <c>IframeBridge</c>でトランスポート<c>MobileApps.Web.js</c>IE8 9 で使用される、します。
             </summary>
        <returns>結果を表す <see cref="T:System.Web.Http.IHttpActionResult" />。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Initialize">
      <MemberSignature Language="C#" Value="protected override void Initialize (System.Web.Http.Controllers.HttpControllerContext controllerContext);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance void Initialize(class System.Web.Http.Controllers.HttpControllerContext controllerContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.Initialize(System.Web.Http.Controllers.HttpControllerContext)" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Sub Initialize (controllerContext As HttpControllerContext)" />
      <MemberSignature Language="F#" Value="override this.Initialize : System.Web.Http.Controllers.HttpControllerContext -&gt; unit" Usage="crossDomainController.Initialize controllerContext" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="controllerContext" Type="System.Web.Http.Controllers.HttpControllerContext" />
      </Parameters>
      <Docs>
        <param name="controllerContext">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoginReceiver">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt; LoginReceiver (string completionOrigin);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Web.Http.IHttpActionResult&gt; LoginReceiver(string completionOrigin) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController.LoginReceiver(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function LoginReceiver (completionOrigin As String) As Task(Of IHttpActionResult)" />
      <MemberSignature Language="F#" Value="member this.LoginReceiver : string -&gt; System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;" Usage="crossDomainController.LoginReceiver completionOrigin" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server.CrossDomain</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Mobile.Server.Controllers.CrossDomainController/&lt;LoginReceiver&gt;d__3))</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.AllowAnonymous</AttributeName>
        </Attribute>
        <Attribute>
          <AttributeName>System.Web.Http.HttpGet</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Web.Http.IHttpActionResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="completionOrigin" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Web.Http.FromUri(Name="completion_origin")</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="completionOrigin">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>