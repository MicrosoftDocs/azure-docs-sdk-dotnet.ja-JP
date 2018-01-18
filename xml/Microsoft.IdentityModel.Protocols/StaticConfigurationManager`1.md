<Type Name="StaticConfigurationManager&lt;T&gt;" FullName="Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;T&gt;">
  <TypeSignature Language="C#" Value="public class StaticConfigurationManager&lt;T&gt; : Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt; where T : class" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit StaticConfigurationManager`1&lt;class T&gt; extends System.Object implements class Microsoft.IdentityModel.Protocols.IConfigurationManager`1&lt;!T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1" />
  <TypeSignature Language="VB.NET" Value="Public Class StaticConfigurationManager(Of T)&#xA;Implements IConfigurationManager(Of T)" />
  <TypeSignature Language="F#" Value="type StaticConfigurationManager&lt;'T (requires 'T : null)&gt; = class&#xA;    interface IConfigurationManager&lt;'T (requires 'T : null)&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
    <AssemblyVersion>2.1.3.0</AssemblyVersion>
    <AssemblyVersion>5.2.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>ReferenceTypeConstraint</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.IdentityModel.Protocols.IConfigurationManager&lt;T&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="f06fe-101">クラスにする必要があります。</span><span class="sxs-lookup"><span data-stu-id="f06fe-101">must be a class.</span></span></typeparam>
    <summary>
            <span data-ttu-id="f06fe-102">この型は、固定と静的構成を使用するユーザーです。</span><span class="sxs-lookup"><span data-stu-id="f06fe-102">This type is for users that want a fixed and static Configuration.</span></span>
            <span data-ttu-id="f06fe-103">ここでは、構成が取得した、コンス トラクターに渡されます。</span><span class="sxs-lookup"><span data-stu-id="f06fe-103">In this case, the configuration is obtained and passed to the constructor.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public StaticConfigurationManager (T configuration);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(!T configuration) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.#ctor(`0)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (configuration As T)" />
      <MemberSignature Language="F#" Value="new Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt; : 'T -&gt; Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt;" Usage="new Microsoft.IdentityModel.Protocols.StaticConfigurationManager&lt;'T (requires 'T : null)&gt; configuration" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="configuration" Type="T" />
      </Parameters>
      <Docs>
        <param name="configuration"><span data-ttu-id="f06fe-104">OpenIdConnectConfiguration または OpenIdConnectConfiguration の種類の構成。</span><span class="sxs-lookup"><span data-stu-id="f06fe-104">Configuration of type OpenIdConnectConfiguration or OpenIdConnectConfiguration.</span></span></param>
        <summary>
            <span data-ttu-id="f06fe-105">新しいインスタンスを初期化<see cref="T:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1" />構成のインスタンスにします。</span><span class="sxs-lookup"><span data-stu-id="f06fe-105">Initializes an new instance of <see cref="T:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1" /> with a Configuration instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConfigurationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;T&gt; GetConfigurationAsync (System.Threading.CancellationToken cancel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!T&gt; GetConfigurationAsync(valuetype System.Threading.CancellationToken cancel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConfigurationAsync (cancel As CancellationToken) As Task(Of T)" />
      <MemberSignature Language="F#" Value="abstract member GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;&#xA;override this.GetConfigurationAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;'T (requires 'T : null)&gt;" Usage="staticConfigurationManager.GetConfigurationAsync cancel" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.GetConfigurationAsync(System.Threading.CancellationToken)</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancel" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancel">
          <span data-ttu-id="f06fe-106"><see cref="T:System.Threading.CancellationToken" /></span><span class="sxs-lookup"><span data-stu-id="f06fe-106"><see cref="T:System.Threading.CancellationToken" />.</span></span></param>
        <summary>
            <span data-ttu-id="f06fe-107">構成の更新バージョンを取得します。</span><span class="sxs-lookup"><span data-stu-id="f06fe-107">Obtains an updated version of Configuration.</span></span>
            </summary>
        <returns><span data-ttu-id="f06fe-108">T 型の構成</span><span class="sxs-lookup"><span data-stu-id="f06fe-108">Configuration of type T.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RequestRefresh">
      <MemberSignature Language="C#" Value="public void RequestRefresh ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void RequestRefresh() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.IdentityModel.Protocols.StaticConfigurationManager`1.RequestRefresh" />
      <MemberSignature Language="VB.NET" Value="Public Sub RequestRefresh ()" />
      <MemberSignature Language="F#" Value="abstract member RequestRefresh : unit -&gt; unit&#xA;override this.RequestRefresh : unit -&gt; unit" Usage="staticConfigurationManager.RequestRefresh " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.IdentityModel.Protocols.IConfigurationManager`1.RequestRefresh</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.IdentityModel.Protocols</AssemblyName>
        <AssemblyVersion>2.1.3.0</AssemblyVersion>
        <AssemblyVersion>5.2.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="f06fe-109">この型では、これは、何も行いません</span><span class="sxs-lookup"><span data-stu-id="f06fe-109">For the this type, this is a no-op</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>