<Type Name="MobileAppConfiguration" FullName="Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration">
  <TypeSignature Language="C#" Value="public class MobileAppConfiguration : Microsoft.Azure.Mobile.Server.Config.AppConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MobileAppConfiguration extends Microsoft.Azure.Mobile.Server.Config.AppConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Class MobileAppConfiguration&#xA;Inherits AppConfiguration" />
  <TypeSignature Language="F#" Value="type MobileAppConfiguration = class&#xA;    inherit AppConfiguration" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Mobile.Server.Config.AppConfiguration</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            指定した構成<see cref="T:System.Web.Http.HttpConfiguration" />Azure Mobile Apps で使用される設定を使用します。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MobileAppConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> クラスの新しいインスタンスを初期化します。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddBaseRouteExclusion">
      <MemberSignature Language="C#" Value="public void AddBaseRouteExclusion (string exclusion);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void AddBaseRouteExclusion(string exclusion) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.AddBaseRouteExclusion(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub AddBaseRouteExclusion (exclusion As String)" />
      <MemberSignature Language="F#" Value="member this.AddBaseRouteExclusion : string -&gt; unit" Usage="mobileAppConfiguration.AddBaseRouteExclusion exclusion" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exclusion" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exclusion">ルートから除外するコント ローラー名。 文字列の末尾には、' Controller' を含めないでください。</param>
        <summary>
            既定のルートを除外するコント ローラー名を追加 'api/{controller}/{id}' です。
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplyTo">
      <MemberSignature Language="C#" Value="public override void ApplyTo (System.Web.Http.HttpConfiguration config);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void ApplyTo(class System.Web.Http.HttpConfiguration config) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.ApplyTo(System.Web.Http.HttpConfiguration)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub ApplyTo (config As HttpConfiguration)" />
      <MemberSignature Language="F#" Value="override this.ApplyTo : System.Web.Http.HttpConfiguration -&gt; unit" Usage="mobileAppConfiguration.ApplyTo config" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="config" Type="System.Web.Http.HttpConfiguration" />
      </Parameters>
      <Docs>
        <param name="config">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="MapApiControllers">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration MapApiControllers ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration MapApiControllers() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.MapApiControllers" />
      <MemberSignature Language="VB.NET" Value="Public Function MapApiControllers () As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="member this.MapApiControllers : unit -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="mobileAppConfiguration.MapApiControllers " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            マップのすべてのコント ローラー、<see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppControllerAttribute" />ルート テンプレートを"api/{controller}/{id}"です。
            </summary>
        <returns>現在の <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithMobileAppControllerConfigProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithMobileAppControllerConfigProvider (Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider provider);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration WithMobileAppControllerConfigProvider(class Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider provider) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration.WithMobileAppControllerConfigProvider(Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMobileAppControllerConfigProvider (provider As IMobileAppControllerConfigProvider) As MobileAppConfiguration" />
      <MemberSignature Language="F#" Value="member this.WithMobileAppControllerConfigProvider : Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider -&gt; Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" Usage="mobileAppConfiguration.WithMobileAppControllerConfigProvider provider" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="provider" Type="Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />
      </Parameters>
      <Docs>
        <param name="provider">登録するプロバイダーです。</param>
        <summary>
            指定した登録<see cref="T:Microsoft.Azure.Mobile.Server.Config.IMobileAppControllerConfigProvider" />で、<see cref="T:System.Web.Http.HttpConfiguration" />です。
            既定のコント ローラーの構成を上書きするのにには、これを使用します。
            </summary>
        <returns>現在の <see cref="T:Microsoft.Azure.Mobile.Server.Config.MobileAppConfiguration" /> です。</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>