<Type Name="AutoHealCustomAction" FullName="Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction">
  <TypeSignature Language="C#" Value="public class AutoHealCustomAction" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit AutoHealCustomAction extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction" />
  <TypeSignature Language="VB.NET" Value="Public Class AutoHealCustomAction" />
  <TypeSignature Language="F#" Value="type AutoHealCustomAction = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="4e842-101">カスタム アクションを実行する自動修復ルールがトリガーされます。</span><span class="sxs-lookup"><span data-stu-id="4e842-101">Custom action to be executed when an auto heal rule is triggered.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealCustomAction ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="4e842-102">AutoHealCustomAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e842-102">Initializes a new instance of the AutoHealCustomAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public AutoHealCustomAction (string exe = null, string parameters = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string exe, string parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.#ctor(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional exe As String = null, Optional parameters As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction : string * string -&gt; Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction" Usage="new Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction (exe, parameters)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="exe" Type="System.String" />
        <Parameter Name="parameters" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="exe"><span data-ttu-id="4e842-103">実行する実行可能ファイル。</span><span class="sxs-lookup"><span data-stu-id="4e842-103">Executable to be run.</span></span></param>
        <param name="parameters"><span data-ttu-id="4e842-104">実行可能ファイルのパラメーターです。</span><span class="sxs-lookup"><span data-stu-id="4e842-104">Parameters for the executable.</span></span></param>
        <summary>
            <span data-ttu-id="4e842-105">AutoHealCustomAction クラスの新しいインスタンスを初期化します。</span><span class="sxs-lookup"><span data-stu-id="4e842-105">Initializes a new instance of the AutoHealCustomAction class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exe">
      <MemberSignature Language="C#" Value="public string Exe { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Exe" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.Exe" />
      <MemberSignature Language="VB.NET" Value="Public Property Exe As String" />
      <MemberSignature Language="F#" Value="member this.Exe : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.Exe" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="exe")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e842-106">取得または設定を実行する実行可能ファイルです。</span><span class="sxs-lookup"><span data-stu-id="4e842-106">Gets or sets executable to be run.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Parameters">
      <MemberSignature Language="C#" Value="public string Parameters { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Parameters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.Parameters" />
      <MemberSignature Language="VB.NET" Value="Public Property Parameters As String" />
      <MemberSignature Language="F#" Value="member this.Parameters : string with get, set" Usage="Microsoft.Azure.Management.WebSites.Models.AutoHealCustomAction.Parameters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Websites</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="parameters")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="4e842-107">取得または実行可能ファイルのパラメーターを設定します。</span><span class="sxs-lookup"><span data-stu-id="4e842-107">Gets or sets parameters for the executable.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>