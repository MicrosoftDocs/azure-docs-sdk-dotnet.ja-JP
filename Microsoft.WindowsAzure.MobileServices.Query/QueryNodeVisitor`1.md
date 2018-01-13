<Type Name="QueryNodeVisitor&lt;T&gt;" FullName="Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor&lt;T&gt;">
  <TypeSignature Language="C#" Value="public abstract class QueryNodeVisitor&lt;T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit QueryNodeVisitor`1&lt;T&gt; extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class QueryNodeVisitor(Of T)" />
  <TypeSignature Language="F#" Value="type QueryNodeVisitor&lt;'T&gt; = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.2.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <typeparam name="T">ビジターが生成するジェネリック型。</typeparam>
    <summary>
            QueryNode ツリーをウォークの訪問者のインターフェイスです。
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected QueryNodeVisitor ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As BinaryOperatorNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.BinaryOperatorNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            BinaryOperatorNode にアクセスします
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.ConstantNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.ConstantNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.ConstantNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As ConstantNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.ConstantNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.ConstantNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.ConstantNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            ConstantNode にアクセスします
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.ConvertNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.ConvertNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.ConvertNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As ConvertNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.ConvertNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.ConvertNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.ConvertNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            ConvertNode にアクセスします
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As FunctionCallNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.FunctionCallNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            ODataMethodCallNode を参照してください。
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As MemberAccessNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.MemberAccessNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            MemberAccessNode を参照してください。
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Visit">
      <MemberSignature Language="C#" Value="public virtual T Visit (Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode nodeIn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !T Visit(class Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode nodeIn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.MobileServices.Query.QueryNodeVisitor`1.Visit(Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function Visit (nodeIn As UnaryOperatorNode) As T" />
      <MemberSignature Language="F#" Value="abstract member Visit : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode -&gt; 'T&#xA;override this.Visit : Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode -&gt; 'T" Usage="queryNodeVisitor.Visit nodeIn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Client</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.2.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeIn" Type="Microsoft.WindowsAzure.MobileServices.Query.UnaryOperatorNode" />
      </Parameters>
      <Docs>
        <param name="nodeIn">アクセスするノード</param>
        <summary>
            UnaryOperatorNode にアクセスします
            </summary>
        <returns>実装者が定義します</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>