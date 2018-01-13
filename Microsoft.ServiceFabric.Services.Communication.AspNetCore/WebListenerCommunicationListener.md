<Type Name="WebListenerCommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener">
  <TypeSignature Language="C#" Value="public class WebListenerCommunicationListener : Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebListenerCommunicationListener extends Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Class WebListenerCommunicationListener&#xA;Inherits AspNetCoreCommunicationListener" />
  <TypeSignature Language="F#" Value="type WebListenerCommunicationListener = class&#xA;    inherit AspNetCoreCommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Service Fabric ステートレスまたはステートフルなサービスの通信リスナーを AspNetCore WebListener に基づいています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebListenerCommunicationListener (System.Fabric.ServiceContext serviceContext, string endpointName, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, string endpointName, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener.#ctor(System.Fabric.ServiceContext,System.String,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener : System.Fabric.ServiceContext * string * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener (serviceContext, endpointName, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext">この通信リスナーが構築される、サービスのコンテキスト。</param>
        <param name="endpointName">リスナーのアドレスを作成するために使用する必要がありますサービス マニフェストで定義されているエンドポイント リソースの名前。</param>
        <param name="build">Microsoft.AspNetCore.Hosting.IWebHost、リスナーによって生成された url は、このデリゲートへの入力として指定されているエンドポイントを作成するデリゲートします。
            これにより、柔軟に必要な場合は、Microsoft.AspNetCore.Hosting.IWebHost を作成する前に url を変更します。</param>
        <summary>
            通信リスナーをコンストラクト AspNetCore WebListener に基づいています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListenerUrl">
      <MemberSignature Language="C#" Value="protected override string GetListenerUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetListenerUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.WebListenerCommunicationListener.GetListenerUrl" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetListenerUrl () As String" />
      <MemberSignature Language="F#" Value="override this.GetListenerUrl : unit -&gt; string" Usage="webListenerCommunicationListener.GetListenerUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.WebListener</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リスナーの url を取得します。 コンス トラクターに渡された endpointName を使用してリスナーの url が作成されます。
            </summary>
        <returns>リスナーの url です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>