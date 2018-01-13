<Type Name="KestrelCommunicationListener" FullName="Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener">
  <TypeSignature Language="C#" Value="public class KestrelCommunicationListener : Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit KestrelCommunicationListener extends Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" />
  <TypeSignature Language="VB.NET" Value="Public Class KestrelCommunicationListener&#xA;Inherits AspNetCoreCommunicationListener" />
  <TypeSignature Language="F#" Value="type KestrelCommunicationListener = class&#xA;    inherit AspNetCoreCommunicationListener" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Service Fabric ステートレスまたはステートフルなサービスの通信リスナーを AspNetCore Kestrel に基づいています。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KestrelCommunicationListener (System.Fabric.ServiceContext serviceContext, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.#ctor(System.Fabric.ServiceContext,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener : System.Fabric.ServiceContext * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener (serviceContext, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext">この通信リスナーが構築される、サービスのコンテキスト。</param>
        <param name="build">Microsoft.AspNetCore.Hosting.IWebHost、リスナーによって生成された url は、このデリゲートへの入力として指定されているエンドポイントを作成するデリゲートします。
            これにより、柔軟に必要な場合は、Microsoft.AspNetCore.Hosting.IWebHost を作成する前に url を変更します。</param>
        <summary>
            Http プロトコルとポート 0 を持つ既定のアドレスを使用して通信リスナーをコンストラクト AspNetCore Kestrel に基づいています。
            Kestrel は、ポート 0 は、url で指定されたときに動的に指定されていない、利用可能なポートにバインドされます。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public KestrelCommunicationListener (System.Fabric.ServiceContext serviceContext, string endpointName, Func&lt;string,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt; build);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Fabric.ServiceContext serviceContext, string endpointName, class System.Func`3&lt;string, class Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, class Microsoft.AspNetCore.Hosting.IWebHost&gt; build) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.#ctor(System.Fabric.ServiceContext,System.String,System.Func{System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost})" />
      <MemberSignature Language="F#" Value="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener : System.Fabric.ServiceContext * string * Func&lt;string, Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener, Microsoft.AspNetCore.Hosting.IWebHost&gt; -&gt; Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener" Usage="new Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener (serviceContext, endpointName, build)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="serviceContext" Type="System.Fabric.ServiceContext" />
        <Parameter Name="endpointName" Type="System.String" />
        <Parameter Name="build" Type="System.Func&lt;System.String,Microsoft.ServiceFabric.Services.Communication.AspNetCore.AspNetCoreCommunicationListener,Microsoft.AspNetCore.Hosting.IWebHost&gt;" />
      </Parameters>
      <Docs>
        <param name="serviceContext">この通信リスナーが構築される、サービスのコンテキスト。</param>
        <param name="endpointName">リスナーのアドレスを作成するために使用する必要がありますサービス マニフェストで定義されているエンドポイント リソースの名前。
            プロトコルとこのエンドポイントで指定されたポートについては、url の作成に使用されます。
            EndpointName が null の場合は、http プロトコルとポート 0 を持つ既定のアドレスが使用されます。
            Kestrel は、ポート 0 は、url で指定されたときに動的に指定されていない、利用可能なポートにバインドされます。
            サービス マニフェストで指定された endpointName が見つからない場合は、これを示す、InvalidOperationException がスローされます。</param>
        <param name="build">Microsoft.AspNetCore.Hosting.IWebHost、リスナーによって生成された url は、このデリゲートへの入力として指定されているエンドポイントを作成するデリゲートします。
            これにより、柔軟に必要な場合は、Microsoft.AspNetCore.Hosting.IWebHost を作成する前に url を変更します。</param>
        <summary>
            通信リスナーをコンストラクト AspNetCore Kestrel に基づいています。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetListenerUrl">
      <MemberSignature Language="C#" Value="protected override string GetListenerUrl ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig virtual instance string GetListenerUrl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Communication.AspNetCore.KestrelCommunicationListener.GetListenerUrl" />
      <MemberSignature Language="VB.NET" Value="Protected Overrides Function GetListenerUrl () As String" />
      <MemberSignature Language="F#" Value="override this.GetListenerUrl : unit -&gt; string" Usage="kestrelCommunicationListener.GetListenerUrl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.AspNetCore.Kestrel</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            リスナーの url を取得します。 コンス トラクターに渡された endpointName を使用してリスナーの url が作成されます。
            EndpointName だった場合、既定値を http プロトコルとポート 0 の url が返されます。
            </summary>
        <returns>リスナーの url です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>